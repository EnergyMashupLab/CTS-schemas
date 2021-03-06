# XML Schema Definitions (XSD) for the CTS rev 0.4
These are restricted ("application") schemas based on those in the OASIS specifications for 

+ WS-Calendar
+ Energy Market Information Exchange (EMIX)
+ Energy Interoperation (EI)
They have been restricted to use only the information needed for the Common Transactive Services (CTS).

In all schemas, complexity was removed by using the minimal PIM conforming schema [WS-CALENDAR MIN](http://docs.oasis-open.org/ws-calendar/ws-calendar-min/v1.0/ws-calendar-min-v1.0.html) for all semantics as used in [WS-Calendar Signals and Streams](http://docs.oasis-open.org/ws-calendar/streams/v1.0/streams-v1.0.html). All schedule objects are based on WS-Calendar Streams to permit inheritance when it makes the market work, and to reduce the many ways a WS-Calendar interval can be communicated to a single model that can be used for all CTS purposes.

Updated October 27, 2020 for consistent date, version and other metadata.

(EML-CTS 1.0)[https://github.com/EnergyMashupLab/eml-cts] uses a further simplification of these schemas expressed in Java.
