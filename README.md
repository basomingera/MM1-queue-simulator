# M/M/1 queue simulator and steady-state comparison
An M/M/1 queue Python3 simulator that compares the simulation results against the steady state results.

In queueing theory, M/M/1 is a queue with 1 server, whereby arrivals follow a Poisson process while job service time is an exponential distribution. [Wikipedia] (https://en.wikipedia.org/wiki/M/M/1_queue)
## Getting Started

This small project has only one file with all codes. All need to simulate is to run the MM1.py file.

### Prerequisites

To run this simulator, your machine needs to have Python 3 installed and matplotlib library. On a Linux machine, this can be installed as follows for example

```
pip install matplotlib
```
By default the debug mode is disabled, but once enabled, the file will print logs as of different timestamp event and will generate a CSV file with detailed data.
## Running the simulator

The simulator code is in the MM1.py file and can be run from any python IDE such as Pycharm, etc.
Using the terminal, you can use this command once in the directory:
```
python3 MM1.py
```

## Built With

This project is developed and tested with Python3.5 using Pycharm on Ubuntu 16.04 LTS machine.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

