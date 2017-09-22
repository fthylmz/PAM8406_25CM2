# PAM8406_25CM2
It's a stereo amplifier, nothing's special about this project, it's partly based on [reference design](http://www.mouser.com/ds/2/115/PAM8406-247303.pdf).

[![Perdon My EN](https://img.shields.io/badge/pardon%20my-EN-orange.svg?style=flat)](https://github.com/fthylmz/pam8406)  [![EAGLE](https://img.shields.io/badge/EAGLE-8.3.2-green.svg?style=flat)](https://github.com/fthylmz/pam8406)
## DETAILS

1. All SMD components are 1206 sized regardless of their advantages over audio designs.
2. Input capacitor should be chosen something over 470uF/6V but the footprint I used has lead size 5mm.
3. The coil I used in LPF part of circuit is from CoilCraft, its product code is JA4575-BL.
4. Etc.

I'm not an EE, or had any educations about this topic, it's just my hobby project I consider to use in my future audio projects.

## TO-DO
- [ ] Make room for bigger decoupling caps and include multi pads for variable input capacitor types \(5mm, 8mm, etc.\) to the design.
- [ ] \(Optional\) Add a boost converter to the circuit.
- [ ] Use more common coils in LPF.
- [X] LPF in front of AVDD may be needed, if it's not just include 0R resistors in place.
- [ ] Make optimizations at audio input part.
- [ ] \(Optional\) Make it **perfect** :punch:.

## TESTS
Never tested but I'm confident. :boom:

## LICENSE

© 2017 Fatih YILMAZ

This project is licensed under the [TAPR Open Hardware License V 1.0](www.tapr.org/OHL) and commercial use is acceptable - see the [LICENSE.txt](LICENSE.txt) file for details.
