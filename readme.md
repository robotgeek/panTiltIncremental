/***********************************************************************************
 *     ______            RobotGeek Pan and Tilt Demo              ______
 *      |  |            Incremental  Analog Control                |  | 
 *      |__|_   _                                            _    _|__|
 *      |____|__|                                            |___|____|
 *  The following sketch will allow you to control a Desktop RobotTurret v3 using
 *  the included RobotGeek Joysticl and RobotGeek Pushbutton
 *
 *  Products
 *    http://www.robotgeek.com/robotgeek-pantilt.aspx
 *    http://www.robotgeek.com/robotgeek-geekduino-sensor-kit
 *    http://www.robotgeek.com/robotgeek-joystick
 *    http://www.robotgeek.com/p/power-supply-6vdc-2a.aspx
 *    
 *    
 *  Wiring
 *    Pan Servo - Digital Pin 9 
 *    Tilt Servo - Digital Pin 10 
 *
 *    Joystick1(Vertica)l   - Analog Pin 0
 *    Joystick2(Horizontal) - Analog Pin 1 
 *    Jumper for pins 9/10/11 should be set to 'VIN'
 *  
 *    NOTE: It is possible to control both pan and tilt with one joystick - this
 *          demo uses 2 for ease of use
 *
 *  Control Behavior:
 *    Moving the joysticks will incrementally move the servo. This means that when you
 *    release the joystick to its 'home' position, the servo will stay in the last place
 *    it was. This allows for fine control over the servo's position.
 *    The Horizontal Joystick will incrementaly move the Pan Servo
 *    The Vertical Joystick will incrementaly move the Tilt Servo
 *
 *  External Resources
 *
 ***********************************************************************************/