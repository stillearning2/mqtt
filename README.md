Lets think about an example,

A facebook group chat, were a member writes a message and all other members in that chat group recieves mesage allmost instantaneously.

## The technology behind its succes is MQTT.. There all member's end devices act as MQTT clients. They sends and recieves messages using a technique called publish and subscribe, and a MQTT 'brocker' which runs in facebook server handles the message transfer between various devices where members accessing the group.
### <br>In this screenshots we can see the same thing.
### <br>Theres a channel named 'channel1'
### <br>Every client connected to that channel will recieve message when published.
