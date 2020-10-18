## What's happening

### claw
* C++ support polishing
* Pending documentation

### libresect and cl-resect
* Mostly done, exposing last bits required by `:claw`

### cl-bodge and trivial-gamekit
* On hold for now: heavy focus is on `:claw` C++ support
* Once initial C++ work on `:claw` is mainlined, I'm going to try to port
  `cl-bodge`/`trivial-gamekit` onto Android via `ECL`

## Plans
* Combine `SDL`, `Filament`, `PhysX` and `Skia` into a tightly coupled, mostly
  foreign, but mobile-capable CL
  [framework](https://github.com/borodust/alien-works) for an upcoming game
