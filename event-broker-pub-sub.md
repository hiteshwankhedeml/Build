# Event Broker, Pub - Sub

**Event broker:**

* Enables the transmission of events between different components of a system
* We can configure our source systems to **publish** their events to this message-orientedmiddleware. The source system will specify the class of the message (that is, **topic**).
* Systems interested in the changes happening (for example, in a particular business object in the source system) can **subscribe** to the event(s), via the event broker, by specifying the topic they are interested (`topic-based filtering`) or it can also be based on the content of the message (`content-based filtering`)
*
