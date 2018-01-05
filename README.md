**OLA Trigger config to be used with LIRC to send infra-red commands using DMX (Art-Net, sACN or via DMX input)**

**Requirements**

* [OLA](https://www.openlighting.org/ola/)
* [LIRC](http://www.lirc.org)
* IR transmitter that is supported by LIRC

**Installation**
  
* Download the [lirc.conf](lirc.conf) file and edit the configuration section.

[OLA trigger documentation](https://www.openlighting.org/ola/advanced-topics/ola-dmx-trigger/)

**Usage** 

* Before running ola_trigger, make sure that olad is running and the universe has been configured with a DMX512 source.  
The config file is provided on the command line:

`ola_trigger lirc.conf`
