
### MEL Expression

MEL : used to communicate between message process.

Context Objects : provides logical grouping for the fields
  
  server : this object provides access to the fields for the hardware , operating system , user and network interfaces
  mule: this object provides access to the fields of the mule instance
  app: this object provides access to the fields of the mule application
  message: this object provides access to the fields of the mule message

Syntax 
#[message.inboundproperties]

Variables:

to access information contained within a flow

flow variables : Retain their values as control passes from one message processor to another within single flow.
Session Variables : Retain their values as control passes from one flow to another within an application.

Syntax
#[flowVars.foo] #[sessionVars.bar]

DotSyntax
#[message.payload.item]


