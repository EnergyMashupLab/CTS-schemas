# JSON Schemas rev 0.4

These JSON files were based on the simplified XML Schemas in the XSD directory. For this project, the 
optionality in EMIX was stripped so the product is always "Energy". In a similar way, the optionality
in EI was also trimmed to remove optionality.

As in the schemas, all Calendar information is now based on [OASIS WS-Calendar Signals and Streams](http://docs.oasis-open.org/ws-calendar/streams/v1.0/streams-v1.0.html), using [WS-Calendar MIN](http://docs.oasis-open.org/ws-calendar/ws-calendar-min/v1.0/ws-calendar-min-v1.0.html) for the semantics
to create a single Time object to be sued for all coding.
