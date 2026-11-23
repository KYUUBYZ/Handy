# Handy


<!--START_SECTION:BOM-TABLE-->
| Item | Qty | Supplier | Cost/item | Total Cost | Link |
| :--- | :---: | :--- | :---: | :---: | :--- |
| Stepper motor + TB6600(driver) + speed controller | 1 | aliexpress | $26.61 | $26.61 | [Link](https://www.aliexpress.com/item/1005007507121836.html) |
| Estimated total shipping | 1 |  |  | $2 |  |
<!--END_SECTION:BOM-TABLE-->

## This is Handy
*Handy*, my 1 axis robot, its main purpose is to understand how planetary reducers and stepper motor without microcontroller works, it has a 6:1 ratio as output and it then transfer the torque from the shaft to the pulley and THEN to the sort of "tower" on the other side.

---

I'm planning to print its entirety with my *3d printer* (AD5X from Flashforge) in PLA and the belt in TPU.
Everything fits together with screws and printed connectors.

## I see no microcontroller in there?
Exactly, that's one of Handy's purpose: understanding how to drive a stepper motor without a microcontroller. I'm gonna use its driver: the TB6600, and a CNC controller/speed controller.
How does it work?

- The TB660 receives input from the PUL pin coming from the CNC controller
- It reads the directions from the DIR pin
- it gives both PWM and electrics signals from the CNC controller
- the TB6600 makes the stepper motor works

<img width="1265" height="723" alt="Handy" src="https://github.com/user-attachments/assets/53f0d729-a8bf-457d-a1c5-0658824dccc0" />

# This is a render of the planetary reducer mechanism it uses, its a 6:1 ratio 

<img width="627" height="436" alt="Handy2" src="https://github.com/user-attachments/assets/f769985e-0094-4cbc-994f-789c1c061e0c" />





