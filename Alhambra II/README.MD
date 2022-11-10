# Alhambra II setup

## Kali Linux(DEBIAN)5.10.0-kali9-amd64

### *[ICEstudio](https://github.com/FPGAwars/icestudio)*
#### ICEstudio v8.0(most stable for OS)
.appimage downloaded made executable from <https://github.com/FPGAwars/icestudio/releases/>

##### Step 1: Installing the dependencies
**Try both**
> sudo apt install python3 python3-pip python3-venv xclip libfuse2
> sudo apt install python3 python3-pip python3-venv xclip

#### Steo 2: Enable APIO FTDI Drivers
If ICE APIO doesn't work try enabling from terminal
> apio drivers --ftdi-enable
