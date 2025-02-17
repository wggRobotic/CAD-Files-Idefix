Our robotic dog features a sturdy yet lightweight design. The skeleton is constructed from 15x15 aluminum profile bars, which provide a strong frame. These bars are connected by custom 3D-printed segments made from PETG, ensuring both flexibility and durability. This combination of materials allows for a modular structure, making Idefix easy to assemble, adjust, and repair.

![Basic_frame](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Basic_frame.png)

For movement, 12 [Waveshare ST3215](https://www.berrybase.de/waveshare-serieller-bus-servo-st3215-30kg-cm-360-grad-magnetischer-encoder-12v) servos are used, with three servos per leg to enable dynamic and precise motion. These servos offer high torque and can be linked together for synchronized movement. Control is managed via the Servo-Board 253 ST/SC, allowing for smooth and reliable actuation of the legs.

![Skeleton](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Idefix_skeleton.png)

The heart and brain of our robotic dog is a Raspberry Pi 4. It serves as the central control unit, managing all computations and coordinating movements. The Servo-Boards 253 ST/SC are connected via USB.

A 18 V [drill battery](https://www.einhell.de/p/4511395-2-0-ah-power-x-change/) is used as the power source, allowing for easy replacement. This enables external charging and quick swapping for uninterrupted operation. The required voltages are generated using two [DC-DC converters](https://www.amazon.de/Bauer-Electronics-12V-Spannungswandler-240W/dp/B09CYX2B4M?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A2MOKX4SH02858&th=1) for powering the servos and one DC-DC converter for the Raspberry Pi.

A [Raspberry Pi camera](https://www.berrybase.de/raspberry-pi-camera-module-3-wide-12mp-b-ware) is installed in the front segment of the robot dog, while a [9-DOF sensor](https://www.berrybase.de/adafruit-9-dof-absolute-orientation-imu-fusion-breakout-bno055) is located in the rear section.

The robot dog's shell is 3D printed from PETG and can be easily secured to the profile frame using two screws.

![Frame](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Idefix.png)

Component | Unit price | Quantity | Total price | Note
-------- | :--------: | :--------: | :--------: | --------
15x15 aluminum profile   | 13.29 €   | 1 | 13.29 €   | [Amazon](https://www.amazon.de/Stangenprofil-15x15-Makerbeam-L%C3%A4nge-schwarz/dp/B078Y9W8SC/ref=sr_1_4?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&crid=1GJEU9D3CQK0S&dib=eyJ2IjoiMSJ9.V4Bvru_V4IovYWOhC_6Quff0VeM-R3mCtjxyHXE5LOc7WlTw4Yfbg-_XnClUXYyITl_NcDxGbUk2Wr0S-3T_XR369IsXxyfkd3jqA6BTY-If--_3viKCl_ef72Jm2ZCGMvLIoMkxbg1y9UVILfdykgXMcIraPqJt7yHsA5SeMd6eLDU9cTxSZ6qYM3BbD7B5umYNUgNbzkOE3DKVJjg-gFxJkxrQBTHE_Zd0JcBXx2i7JMz0hbHRaoPhsMytBZ4IpG2YCoVmCM3DWbHt5JYfwIM8yULrxPDRweJtYioICgkfclGo2mvhdx0ryzKUS6XCRm6W0l_jjTCRU9o3M_A2sh-Bvll6CLWkZ-BZllIgLdA.fX2TywhcB2IpPlJ9tf3JksUCtF-NljY46DNEWhvgA4s&dib_tag=se&keywords=aluprofil+15x15&qid=1739821144&s=industrial&sprefix=aluprofil+15x15%2Cindustrial%2C82&sr=1-4)
Waveshare ST3215   | 22.90 €   | 12 | 274,80 €   | [BerryBase](https://www.berrybase.de/waveshare-serieller-bus-servo-st3215-30kg-cm-360-grad-magnetischer-encoder-12v)
Raspberry Pi 4  | 59.90 €   | 1 | 59.90 €   | [BerryBase](https://www.berrybase.de/raspberry-pi-4-computer-modell-b-4gb-ram)
ServoBoard 253 ST/SC | 4.40 € | 2 | 8.80 € | [BerryBase](https://www.berrybase.de/waveshare-serielle-bus-servo-adapterplatine-253-st-sc-serie-steuerung-fuer-roboterarm-hexapod)
Raspberry Pi Camera Module | 39.90 € | 1 | 39.90 € | [BerryBase](https://www.berrybase.de/raspberry-pi-camera-module-3-wide-12mp)
9-DOF sensor | 36.90 € | 1 | 36.90 € | [BerryBase](https://www.berrybase.de/adafruit-9-dof-absolute-orientation-imu-fusion-breakout-bno055)
DC-DC Converter | 24.99 € | 2 | 49.98 € | [Amazon](https://www.amazon.de/Bauer-Electronics-12V-Spannungswandler-240W/dp/B09CYX2B4M?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&smid=A2MOKX4SH02858&th=1)
Bambu PETG Filament 1 kg  | 16.99 € | 2 | 33.98 € | [Bambu](https://eu.store.bambulab.com/de/products/petg-hf?variant=49068714623324)
Drill Battery | 35.95 € | 1 | 35.95 € | [Einhell](https://www.einhell.de/p/4511395-2-0-ah-power-x-change/)
|  | |**TOTAL:** | 523.50 € |
