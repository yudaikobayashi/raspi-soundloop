# raspi-soundloop
Raspberry Pi as a Drum Machine.

You need two external switch connected to GPIO pins.
First switch will play/stop a sound loop.
Another one will play a sound effect.

The pygame library controls the sounds.


RESULT: Fail.
I used the gpiozero.Button module to play/stop the sound loop,
and it takes TOO LONG time to respond.
Musicians are not capable to accept these kind of delay.
