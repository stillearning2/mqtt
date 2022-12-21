### Lets think about an example,

### A facebook group chat, were a member writes a message and all other members in that chat group recieves mesage allmost instantaneously.

## The technology behind its succes is MQTT.. There all member's end devices act as MQTT clients. They sends and recieves messages using a technique called publish and subscribe, and a MQTT 'brocker' which runs in facebook server handles the message transfer between various devices where members accessing the group.
### <br>In this screenshots we can see the same thing.
### <br>Theres a channel named 'channel1'
### <br>Every client connected to that channel will recieve message when published.

![Screenshot from 2022-12-21 23-15-32](https://user-images.githubusercontent.com/76256496/208972316-3d088523-5116-472e-8eee-56d4301d541f.png)
![Screenshot from 2022-12-21 23-15-23](https://user-images.githubusercontent.com/76256496/208972648-891ee295-71a3-463a-8bca-bbed2566017a.png)
![Screenshot from 2022-12-21 23-15-28](https://user-images.githubusercontent.com/76256496/208972661-047f2001-0971-4898-aa67-a6735c269374.png)
![Screenshot from 2022-12-21 23-15-32](https://user-images.githubusercontent.com/76256496/208972682-c0df3870-cb7f-436f-ae3f-fb2671361c14.png)
