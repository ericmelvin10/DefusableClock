# DefusableClock


  Defusable Clock Firmware
  Copyright (C) 2011 nootropic design, LLC
  All rights reserved.

  This library is free software; you can redistribute it and/or
  modify it under the terms of the GNU Lesser General Public
  License as published by the Free Software Foundation; either
  version 2.1 of the License, or (at your option) any later version.

  Countdown begins when red DET button is pressed. Default countdown
  duration is 10 seconds.

  To increase countdown time, hold the red DET button then press HOUR
  and MIN buttons to increase minutes and seconds before releasing
  the DET button.

  To decrease countdown time, hold the red DET button and the ALARM
  button, then press HOUR and MIN buttons to decrease minutes and seconds.

  If the countdown duration is changed, it will be remembered next time
  the device is powered on.

  At detonation, trigger goes HIGH for 3 seconds. To change trigger duration,
  change TRIGGER_DURATION_MS.



ES
  Modificado por ericmelvin10 (Adrian Aceituno) en 2015 para una partida de ROL-paintball.
  El diseño inicial de nootropic permitia desactivar la bomba cortando tan solo un cable, que era elegido de forma aleatoria.
  En mi diseño, hay que cortar los cables en un orden determinado para desactivarla, para ello he añadido una sencilla máquina de estados.

  Para poder usarlo, debes utilizar una placa de arduino que permita pinchar la eprom que viene en la placa del defusable clock, programar la eprom y volverla a instalar en la     placa de nootropic. 
  
EN
  Modified by ericmelvin10 (Adrian Aceituno) in 2015 for a role paintaball game.
  Nootropic aproach to defuse was based in cutting a random cable. 
  I replaced that function with a simple state machine forcing to cut the cables in a certain order.
  
  To use the code, you must use an arduino board compatible with the eprom used by nootropic in the defusable clock. You should reprogram the eprom by placing the chip in the     arduino board, then upload the code to the eprom, and put it back to the nootropic defusable clock board.
  
https://nootropicdesign.com/defusable-clock/



