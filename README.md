# MEGA_MIDI_Controller
Arduino MEGA-based MIDI Controller

I had a similar project years ago (MIDIconvertor -- and looking at the code, it was pretty awful). I had been working on my VMC project, but had issues with implementation of the multiplexers, so I decided to dig my MEGA out of storage to at least get 16 MIDI controls working.

This project makes use of the hairless-midiserial program (http://projectgus.github.com/hairless-midiserial/) as the MEGA is sending the data via USB serial and the data needs to be converted on the workstation.

This works with potentiometers only at this point -- and I don't have plans to expand to buttons or encoders anytime soon -- so it's pretty straight forward.
