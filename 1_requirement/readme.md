
![SWOT A](https://user-images.githubusercontent.com/71684969/146224380-f09c1315-e5db-4441-9420-8b970bd9a05b.png)



## 4W's and 1H

WHEN

Whenever there is an unsolved Rubik's cube this project helps in solving it. 

WHAT

This project is concerned about solving the Rubik's cube by using layer by layer method.

WHOM

Anyone who doesn't know how to solve the Rubik's cube can use this project.
 
HOW

Implemented using structure, pointers, enum and other functionalities of C.

Basic requirements that are very essential are:

1)A rubik's cube application or a real rubik's cube.
2)gcc compiler with a good system.
3)Any of the two linux/windows.

## DETAILS REQUIREMENTS
## High Level Requirements 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to provide colors present in the rubik’s cube. | Techincal | IMPLEMENTED | 
| HR02 | User shall be able to solve a Rubik’s cube from any starting condition. | Techincal | IMPLEMENTED |
| HR03 | User shall be able to see all the steps needed to solve the rubik's cube along with the colors displayed on the console. | Techincal | IMPLEMENTED |
| HR04 |User shall be able to solve the Rubik's cube layer by layer. | Techincal | IMPLEMENTED |
| HR05 | User should be able to solve the cube in minimum number of steps. | Techincal | FUTURE |
| HR06 | Displaying a message while the program is figuring out the solution would greatly improve the ease of use | Scenario | FUTURE |
| HR07 |Adding an option to view general Rubik's cube algorithms which will increase the uses of solving it easily. | Techincal | FUTURE |

### Low level Requirements
 
| ID | Functions | Description | HLR ID | Status (Implemented/Future) |
| ------ |------- |--------- | ------ | ----- |
|LR01| Isnode valid | checks if all the Nodes entered by the user is valid or not|HR01|IMPLEMENTED|
|LR02| Is rubecube valid | checks if the entered colors of rubiks cube have 6 colors where 9 are of same suit |HR01|IMPLEMENTED|


| ID | Functions | Description | HLR ID | Status (Implemented/Future) |
| ------ |------- |--------- | ------ | ----- |
|LR03| Isnode valid | performs rotate operation on the front layer|HR01|IMPLEMENTED|
|LR04| Is rubecube valid | performs rotate operation on the middle layer |HR03|IMPLEMENTED|
|LR05| Isnode valid | performs rotate operation on the back layer|HR03|IMPLEMENTED|
|LR06| Is rubecube valid | performs horizontal motion on upper layer |HR03|IMPLEMENTED|
|LR07| Isnode valid | performs horizontal motion on the middle layer|HR03|IMPLEMENTED|
|LR08| Is rubecube valid | performs horizontal motion on the down layer |HR03|IMPLEMENTED|
|LR09| left vertical | performs vertical motion on the left layer |HR03|IMPLEMENTED|
|LR10| middle vertical | performs vertical motion on the middle layer |HR03|IMPLEMENTED |
|LR11| right vertical | performs vertical motion on the right layer |HR03|IMPLEMENTED |
