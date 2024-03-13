# Build notes

I had to do a 

>    git submodule update --init --recursive

before I could get the build to happen

SITL build is:

> ./waf configure --board sitl
> ./waf build rover

You should then find the binary in the `build/sitl/bin` directory.