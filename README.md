# zephyrNotes

Personal Notes to the usage of zephyr


## ZEPHYR OS EXPERIENCE AND DOCUMENTATION

This project is a documentation of my experience with the Zephyr operating system, including setup guides, usage tips, and other relevant information.
Table of Contents

    Getting Started
    Hardware Requirements
    Installation
    Basic Usage
    Advanced Features
    Acknowledgments

### Getting Started

Before you begin, make sure that your hardware meets the minimum requirements for running Zephyr. You will also need to have a basic understanding of Linux systems and be comfortable with using the command line.

Hardware Requirements I use the nrf52840_dk as the designated Hardware which is simulated with Renode.

Zephyr supports a wide range of hardware, but your device must meet the following minimum requirements in order to run Zephyr:

    CPU: A 32-bit or 64-bit ARM Cortex-M based CPU
    Memory: At least 64MB of RAM
    Storage: At least 512MB of flash memory or a similar storage solution
    Network: A network interface that supports Ethernet or Wi-Fi

### Installation

I use PlatformIO as a extention for Visual studio code, sadly as of writing this it is not available for VsCodium.

Aditionaly I use Renode for testing, you could alternativly test on hardware.



#### Renode 

A simulation environment for microcontrollers.

Follow the instruction on these repositories.

https://github.com/renode/renode

#### PlatformIO

Install VSC and then install the extention in VSC.


### Basic usage

Using Platform-IO create project and copy needed .c and .h files as well as coping every content of the `` \zephyr `` folder.

To compile, use the compile button in the toolbar at the bottom.

In case of multiple projects, select which to build.

### Acknowledgments

The Zephyr documentation has most things but not easily understandable, therefore I created this to generate more complex and understandable examples.

# What this is not

A complete guide to zephyr, if you want that, read the official documentation.

As I fill this with my experience while creating projects, it is not always the best way, but a way that works somehow.

I only do this for the Board nrf25840 as it is the bard for my projects. therfore I do not have expierence with other platforms.

