**[pygame-joystick-test][]** is a small Python program that uses [pygame][] to test joysticks. Upon running, it shows the state (axes, trackballs, hats and buttons) of all detected joysticks. It's a quick and simple way to check how well your joystick works. It was written in 2007-09-09 using Python 2 and that code still runs in 2020 in Python 3.

Requirements:

* Python 2 or 3
* [pygame][] 1.x or 2.x
    * I expect `pygame-joystick-test` to be compatible with any system that is supported by `pygame`.
* At least one joystick (or gamepad or any kind of game controller) connected to the system.
    * This tool refuses to start unless it detects at least one joystick.

[![pygame-joystick-test demonstration, with two gamepads connected][gif]][gif]

[pygame-joystick-test]: https://github.com/denilsonsa/pygame-joystick-test
[pygame]: https://www.pygame.org/
[gif]: http://denilsonsa.github.io/pygame-joystick-test/pygame-joystick-test.gif
