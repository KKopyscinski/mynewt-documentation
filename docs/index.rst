Apache Mynewt Documentation
===========================

.. toctree::
   :hidden:
   :titlesonly:

   get_started/index
   newt/index


Welcome to Apache Mynewt
~~~~~~~~~~~~~~~~~~~~~~~~

Apache Mynewt is an operating system that makes it easy to develop
applications for microcontroller environments where power and cost are
driving factors. Examples of these devices are connected locks, lights,
and wearables.

Microcontroller environments have a number of characteristics that makes
the operating system requirements for them unique:

-  Low memory footprint: memory on these systems range from 8-16KB (on
   the low end) to 16MB (on the high end).

-  Reduced code size: code often runs out of flash, and total available
   code size ranges from 64-128KB to 16-32MB.

-  Low processing speed: processor speeds vary from 10-12MHz to
   160-200MHz.

-  Low power operation: devices operate in mostly sleeping mode, in
   order to conserve battery power and maximize power usage.

As more and more devices get connected, these interconnected devices
perform complex tasks. To perform these tasks, you need low-level
operational functionality built into the operating system. Typically,
connected devices built with these microcontrollers perform a myriad of
functions:

-  Networking Stacks: Bluetooth Low Energy and Thread

-  Peripherals: PWM to drive motors, ADCs to measure sensor data, and
   RTCs to keep time.

-  Scheduled Processing: actions must happen on a calendared or periodic
   basis.

Apache Mynewt accomplishes all the above easily, by providing a complete
operating system for constrained devices, including:

-  A fully open-source Bluetooth Low Energy stack with both Host and
   Controller implementations.

-  A pre-emptive, multi-tasking Real Time operating system kernel


-  A Hardware Abstraction Layer (HAL) that abstracts the MCU's
   peripheral functions, allowing developers to easily write
   cross-platform code.
