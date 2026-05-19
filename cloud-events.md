# Cloud Events

* Specification for describing event data in a common way
* It mainly composes of version, type, id, data etc&#x20;

{\
"specversion" : "1.0",\
"type" : "com.github.pull\_request.opened",\
"source" : "https://github.com/cloudevents/spec/pull",\
"subject" : "123",\
"id" : "A234-1234-1234",\
"time" : "2018-04-05T17:31:00Z",\
"comexampleextension1" : "value",\
"comexampleothervalue" : 5,\
"datacontenttype" : "text/xml",\
"data" : "\<much wow="xml"/>"\
}
