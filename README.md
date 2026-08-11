*This project has been created as part of the 42 curriculum by jenlee*

# NetPractice

NetPractice is a 42 networking project focused on understanding and configuring basic networks. The project is completed through a training interface composed of several progressive levels, where the goal is to make hosts communicate correctly by setting up IP addresses, subnet masks, gateways, routes, switches, and routers.

## Description

The goal of this project is to discover and practice fundamental networking concepts in a guided environment. Each level presents a small network topology that must be configured so that the required machines can communicate.

Through the different levels, the project covers:

- IPv4/TCP/IP addressing;
- subnet masks and network boundaries;
- default gateways;
- routing between several networks;
- basic behavior of switches and routers;
- interpretation of network diagrams;
- validation of connectivity inside a simulated network.

The project is not only about making a level pass, but also about understanding why a given address, mask, gateway, or route is required for communication to work.

## Instructions

### Prerequisites

To run the training interface, you need:

- a Unix-like environment, such as Linux or macOS;
- Bash;
- a modern web browser;
- any local dependencies required by `run.sh`, if your version of the project uses a local web server.

No manual compilation step is required for the base training interface. If your repository includes a `Makefile` or another build system, compile the project first before running it.

### Installation

Clone the repository and move into the project directory:

```bash
git clone YOUR_REPO_URL
cd netpractice
bash run.sh
```
