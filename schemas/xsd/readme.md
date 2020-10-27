# XML Schema Definitions (XSD) for the CTS rev 0.4
These are restricted ("application") schemas based on those in the OASIS specifications for 

+ WS-Calendar
+ Energy Market Information Exchange (EMIX)
+ Energy Interoperation (EI)
They have been restricted to use only the information needed for the Common Transactive Services (CTS).

In all schemas, complexity was removed by using the minimal PIM conforming schema (WS-CALENDAR MIN) for all semantics. All schedule objects are based on WS-Calendar STREAMS to permit inheritance when it makes the market work, and to reduce the many ways a WS-Calendar internal can be communicated to a single model that can be used for all CTS purposes.

Updated October 27, 2020 for consistent date, version and other metadata.

(EML-CTS 1.0)[https://github.com/EnergyMashupLab/eml-cts] uses a further simplification of these schemas expressed in Java.
