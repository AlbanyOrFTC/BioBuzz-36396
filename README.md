# BioBuzz-36396

FIRST ROBOTICS FTC 
Team Albany Volts

This is a collection all all created programming files used in the 2026-2027 BioBuzz season.

To upload one of these files:

1) Plug in battery and turn on robot
2) Connect to robot over wifi on both driver station and laptop
3) On driver station, click on the three dots in the corner
4) Click on Program and Manage. There should be an IP address listed
5) On laptop, navigate to that IP address
6) You should now be on the FIRST Robot Controller Console
7) Click on the OnBotJava tab
8) Either upload new file or paste changes that need to be made

To set up motors:

1) Plug in battery and turn on robot
2) On driver station, click on the three dots in the corner
3) Click on Configure Robot
4) Either click New for a new hardware mapping or click on Edit to edit an existing hardware mapping
5) Enter the type of motor plugged into each port
6) Enter the associated name
EX: From code: leftDrive = hardwareMap.get(DcMotor.class, "left_drive");
If the motor that controls the left drive is plugged into port 0, under port 0 enter " left_drive "

