# Event tickets - UML
UML diagrams (activity, sequence, states, data model) for Blockchain events ticket system PoC.

## Description
The idea for this proof of concept consists in creating a **Events ticket system**.
- A event organizer can create a specific event and assign it some properties (date, type, location, price, ...)
- The organizer can decide later to put the event tickets for sale. From this moment the event attendees can buy a ticket.
- The attendee can presents the ticket using the corresponding smartphone App at the event's location at the proper date. The smartphone of the attendee communicates with the smartphone of the validator (through QR code for example), sending the respective ticket id and buyer addresses.
- The validator (security employee, door controller...) can then process the presented ticket and validate it.
- If the ticket is valid for this event and user, then the entry of the attendee is allowed, otherwise it is denied.

## Actors
* Organizer
* Attendee
* Validator

## Content:
1. Activity diagram
2. Sequence diagram
3. States diagram
4. Data model diagram
