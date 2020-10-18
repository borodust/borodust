## What's happening

### claw
* C++ support polishing

### cl-bodge and trivial-gamekit
* On hold for now: heavy focus is on `:claw` C++ support
* Once initial C++ work on `:claw` is mainlined, I'm going to try to port
  `cl-bodge`/`trivial-gamekit` onto Android via `ECL`
* Possibly, most dependencies will be replaced with `alien-works`

### alien-works
* Mostly foreign, but mobile-capable game foundation [framework](https://github.com/borodust/alien-works)
* Uses a lot of `C` and `C++` libraries which is a perfect ground to find
  `:claw` bugs and missing features
