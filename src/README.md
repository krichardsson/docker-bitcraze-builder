# Bitcraze-builder

This image can be used to build code for the Bitcraze Crazyflie.

# Usage

You can for instance type something like

    docker run --rm -v "$PWD":/tmp krichardsson/bitcraze-builder make

This will add your current directory, as a volume, to the container, and run the command `make` 
