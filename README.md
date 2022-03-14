# eventserver
an event server that takes stream of inputs and emits events to any attached clients

## Basics

Pre-event system:
Canvas Hand = Left hand palm open
when canvas hand == present in view plane
then, emit position events

 
Event system:
load patterns
check if continuous positions match any events
if so, then emit events trigger to clients

Event = a collection of positions and a name
