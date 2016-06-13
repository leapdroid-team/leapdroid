# leapdroid
Leapdroid Android emulator

Leapdroid is an Android emulator running on desktop, see www.leapdroid.com. It runs the whole Android system on desktop PC. Most people use Leapdroid to play Android games with bigger screens.

The architecture of Leapdroid is simple: Virtual box as VM engine, and modified Android as guest image. On top of that, we developed state-of-the-art virtual machine technologies to improve performance, user experience and gaming compatibility. Some of our key technical components are:

  - LeapGL, a cross platform OpenGL translator that enables us to run OpenGL ES natively on host desktop. 
  - LeapIO, a light weight RPC infrastructure between guest and host. Our Adb and other services are built on top of LeapIO.

We plan to open source some of our technologies to benefit the community.







