# .func and .meas

## impedance with .ac
.func Z() V(Z+,Z-)/I(Vsense)

.func Y() 1/Z()

.func Rs() re(Z())

.func Cs() -1/2/pi/freq/im(Z())

.func Ls() im(Z())/2/pi/freq

.func Rp() 1/re(Y())

.func Cp() im(Y())/2/pi/freq

.func Lp() -1/2/pi/freq/im(Y())



