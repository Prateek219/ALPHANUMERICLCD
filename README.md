# ALPHANUMERIC LCD
### This document will tell you working of 16x2 alphanumeric lcd
## Basic Pin & Description:

![Screenshot (44)](https://user-images.githubusercontent.com/64007722/79751921-0b090c80-8331-11ea-962b-6391bb9b8514.png)
___
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


  ##### BIT INITIALIZATION

![Screenshot (46)](https://user-images.githubusercontent.com/64007722/79752754-6c7dab00-8332-11ea-8c36-4fe9da7d4f56.png)


  ##### BIT INITIALIZATION

![Screenshot (47)](https://user-images.githubusercontent.com/64007722/79753065-f0379780-8332-11ea-9288-62bda9543200.png)
___

### INSTRUCTION SET
![Screenshot (48)](https://user-images.githubusercontent.com/64007722/79753153-19f0be80-8333-11ea-9b3a-76152e6289c1.png)
___

## SCAN CODE 
![Screenshot (49)](https://user-images.githubusercontent.com/64007722/79753287-486e9980-8333-11ea-96e2-b0554f8e18db.png)
#### Note: Software initialisation is always preferred.

