# Hotel Reservation

Hotel reservation system consisting of multiple software components; developed as part of a uni pair assignment. Microservice-style package architecture.

This project is a pair assignment conducted as part of the [Software Components (4025)](https://raf.edu.rs/knjiga-predmeta/softverske-komponente/) course at the [School of Computing, Union University](https://raf.edu.rs/?pismo=lat).

**NOTE:** Please note that all of the project's documentation is in Serbian. Some parts of the project may have been ommitted due to restricted access.

The project consists of the following submodules:

| Component | Description |
| --- | --- |
| [sk.api](https://github.com/andrejanesic/sk.api/) | The API that glues all distributed components together. |
| sk.gateway | Gateway for accessing services inside the cluster; used for load-balancing. |
| [sk.client](https://github.com/Aleksa0308/sk.client) | Front-end server for creating user profiles, editing reservations, etc. Developed in Node. Communicates with the API via the gateway. |

## Authors

[![Andreja Nesic](https://andrejanesic.com/git-signature-sm.png)](https://andrejanesic.com)

Aleksa Stojanovic<br>
Student @ [School of Computing, Union University](https://raf.edu.rs/?pismo=lat)<br>
https://github.com/Aleksa0308