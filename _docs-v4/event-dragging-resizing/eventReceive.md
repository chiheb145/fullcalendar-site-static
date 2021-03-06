---
title: eventReceive
type: callback
---

Called when an [external draggable element](external-dragging) with associated [event data](event-parsing) was dropped onto the calendar. Or an event [from another calendar](other-calendar-dragging).

<div class='spec' markdown='1'>
function( *info* ) { }
</div>

`info` is a plain object with the following properties:

<table>

<tr>
<th>draggedEl</th>
<td markdown='1'>
The HTML element that was being dragged.
</td>
</tr>

<tr>
<th>event</th>
<td markdown='1'>
An [Event object](event-object) containing the newly created/received event.
</td>
</tr>

<tr>
<th>view</th>
<td markdown='1'>
The current [View Object](view-object).
</td>
</tr>

</table>


## Resources

When an event has been dropped on a resource, the `event`'s resources will reflect.
