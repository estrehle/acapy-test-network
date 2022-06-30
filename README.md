# acapy-test-network

Run a local network consisting of a [Hyperledger Indy](https://www.hyperledger.org/use/hyperledger-indy) ledger ([VON Network](https://github.com/bcgov/von-network))
and three [Hyperledger Aries](https://www.hyperledger.org/use/aries) agents ([ACA-Py](https://github.com/hyperledger/aries-cloudagent-python)).

## Getting Started

The script was tested on Ubuntu 20 in Windows Subsystem for Linux (WSL2).

### Prerequisites:
- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Manage Docker as non-root user](https://docs.docker.com/engine/install/linux-postinstall/#manage-docker-as-a-non-root-user)

Clone this repo and change into the directory:
````
git clone https://github.com/estrehle/acapy-test-network.git
cd acapy-test-network
````

### Start the network
To start the network, run `./start`.

Information on the three Aries agents:
| Agent name    | Public DID               | Admin interface       |
|---------------|--------------------------|-----------------------|
| Aries 1 Agent | `4cLztgZYocjqTdAZM93t27` | http://localhost:8001 |
| Aries 2 Agent | `JDmZmbYJnRyz5mb5U9wCxK` | http://localhost:8002 |
| Aries 3 Agent | `NhSTz5qnEnUtR4eD3pef4N` | http://localhost:8003 |

### Stop the network
To stop the network, press <kbd>Ctrl</kbd> + <kbd>c</kbd> and run `./stop`.
