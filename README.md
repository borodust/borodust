## What's happening

### alien-works
* Game foundation [framework](https://github.com/borodust/alien-works) for Common Lisp
* All required C and C++ foreign libraries are now integrated into `:alien-works`
* Next step is making an actual but smol game to smoke out obvious quirks and
  have a better idea how convenient and lispy API could look like without
  sacrificing any performance
  * And for that I need solid application [delivery mechanism](https://github.com/borodust/alien-works-delivery)

### claw
* More C++ libraries wrapped - more edge-cases discovered, but autowrapping is more or less solid now
  * Many C and C++ libraries were wrapped (even including C++ [enterprise solutions](https://github.com/borodust/cl-dcmtk))
* Preparing for public beta release

### cl-bodge and trivial-gamekit
* On hold for now: heavy focus is on `:claw` C++ support and `:alien-works` prototyping
