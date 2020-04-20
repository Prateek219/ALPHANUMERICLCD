# ALPHANUMERIC LCD
### This document will tell you working of 16x2 alphanumeric lcd
## Basic Pin & Description:

![Screenshot (44)](https://user-images.githubusercontent.com/64007722/79751921-0b090c80-8331-11ea-962b-6391bb9b8514.png)
## Initialization Protocol :
### 1. Initialization using the Internal Reset Circuit
The display can be initialized using the internal reset circuit if the Internal Power Supply Reset timing
below is met.
![Screenshot (45)](https://user-images.githubusercontent.com/64007722/79752142-7226c100-8331-11ea-8d55-016ab9e71813.png)
Note: toff represents the time of power off condition for a momentary power supply dip or when cycling power
off then on.
 If the internal power supply reset timing cannot be met, the display will not operate normally. In this case,
 the display can be initialized through software.
Note: Variable power supply may affect timing hence initialization of lcd in that case software initialization is
 preferred.
 ### 2. Software Initialization
Although software initialization is not mandatory, it is recommended that this procedure always be
performed

