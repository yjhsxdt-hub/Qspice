# .func and .meas

## impedance with .ac
.func Z() V(Z+,Z-)/I(Vsense)<br/>
.func Y() 1/Z()<br/>
.func Rs() re(Z())<br/>
.func Cs() -1/2/pi/freq/im(Z())<br/>
.func Ls() im(Z())/2/pi/freq<br/>
.func Rp() 1/re(Y())<br/>
.func Cp() im(Y())/2/pi/freq<br/>
.func Lp() -1/2/pi/freq/im(Y())<br/>



