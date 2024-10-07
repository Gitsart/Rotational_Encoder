# Rotational_Encoder
Test_Codes for rotary encoder to measure speed of a rotating object. Using MEGA and IDE
Encoder is coupled to a rotary mechanism like a conveyor belt whcih moves at an unknown RPM (HostMachine);
For the test case the code : MOTOR ROTATE is used to make a stepper rotate continuosly in one direction. The speed is controlled through program variable setSpeed;
The system is coupled to an the encoder using a tootj belt system using pulley shaft couping  (GT2 pulley);
Both motor and encoder is equipped with a gt2 of same size for no difference in the gear ratio.
The encoder will rotate with the same speed as of the motor (slightly higher 2 or 3 RPM) .
The test codes print RPM can read the RPM of the encoder and prnt it on the serial monitor provided the connections are correct.
As the last of the test phase the encoder signal is being given to the CPU of the autostacker so that the system can read the RPM data from the encoder.
This RPM from the encoder is read and manipulated in the stacker logic and according to the speed of the conveyor the speed of the forward stroke of the collection is automatically adjusted by the stacker logic.
Reversestroke speed is entirely dependent on the program.
