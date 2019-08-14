# Daffodil + level shifter
A GreatFET Neighbor for prototyping GreatFET neighbors!

Also useful for prototyping other circuits. This fork includes a bi-directional level shifter based on BSS138 FETs and 10k pullups (instead of the original proto area). The level shifter can be used to connect up to four of GreatFET's I/O channels to a low voltage periphery. It works down to 1.8V for any bi- or uni-directional signal up to 2MHz (I2C, SPI, TTL).

Required KiCad dependency:

https://github.com/greatscottgadgets/gsg-kicad-lib

If you are using git, the preferred way to install gsg-kicad-lib is to use the
submodule:

```
git submodule init && git submodule update
```
