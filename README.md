Our robotic dog features a sturdy yet lightweight design. The skeleton is constructed from 15x15 aluminum profile bars, which provide a strong frame. These bars are connected by custom 3D-printed segments made from PETG, ensuring both flexibility and durability. This combination of materials allows for a modular structure, making Idefix easy to assemble, adjust, and repair.

![Basic_frame](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Basic_frame.png)

For movement, 12 [Waveshare ST3215](https://www.berrybase.de/waveshare-serieller-bus-servo-st3215-30kg-cm-360-grad-magnetischer-encoder-12v) servos are used, with three servos per leg to enable dynamic and precise motion. These servos offer high torque and can be linked together for synchronized movement. Control is managed via the Servo-Board 253 ST/SC, allowing for smooth and reliable actuation of the legs.

![Skeleton](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Idefix_skeleton.png)

The heart and brain of our robotic dog is a Raspberry Pi 4. It serves as the central control unit, managing all computations and coordinating movements. The Servo-Boards 253 ST/SC are connected via USB.

A 18 V [drill battery](https://www.einhell.de/p/4511395-2-0-ah-power-x-change/) is used as the power source, allowing for easy replacement. This enables external charging and quick swapping for uninterrupted operation. The required voltages are generated using two [DC-DC converters](https://www.amazon.de/Bauer-Electronics-12V-Spannungswandler-240W/dp/B09CYX2B4M?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A2MOKX4SH02858&th=1) for powering the servos and one DC-DC converter for the Raspberry Pi.

A [Raspberry Pi camera](https://www.berrybase.de/raspberry-pi-camera-module-3-wide-12mp-b-ware) is installed in the front segment of the robot dog, while a [9-DOF sensor](https://www.berrybase.de/adafruit-9-dof-absolute-orientation-imu-fusion-breakout-bno055) is located in the rear section.

The robot dog's shell is 3D printed from PETG and can be easily secured to the profile frame using two screws.

![Frame](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Idefix.png)
