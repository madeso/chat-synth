# Polyphonic Software Synthesizer

This is a modern C++ implementation of a polyphonic software synthesizer that supports instruments and loads music files from the commandline. It does not have any external dependencies and is able to play a sample song file for Tjajkovskij's "Swan Lake".
Building the Synthesizer

To build the synthesizer, follow the steps below:

1. Install CMake on your system.
1. Clone or download this repository.
1. Open a terminal and navigate to the directory where the repository was cloned or downloaded.
1. Create a build directory and navigate to it.
1. Run the following command to generate the build files for the synthesizer:
    cmake ..
1. Run the following command to build the synthesizer:

    make

1. The executable file for the synthesizer will be generated in the build directory.

## Running the Synthesizer

To run the synthesizer, follow the steps below:

1. Open a terminal and navigate to the build directory.
2. Run the following command to play the sample song file for Tjajkovskij's "Swan Lake" using the synthesizer:
  ``./synthesizer swan_lake.txt``
  where "synthesizer" is the name of the executable file and "swan_lake.txt" is the name of the sample music file.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
