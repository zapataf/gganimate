# gganimate (development version)

* Fix bug in transitions when the group aesthetic was late evalued (#262)
* Better fade support for `geom_smooth()`. Both ribbon and line will now fade.
* Fix bug in transitions when group aesthetic was a string that could be 
  interpreted as a double (#266)
* Fix bug in `shadow_mark()` where future shadows were drawn above the main 
  frame data.
* Better error messages when a layer type is not supported by the transition
* Fix bug where transitions didn't work with difftime/hms for specifying 
  durations when transition variable was a POSIX or date class.
* Fix bug where using a view would modify the plot coordinate system in-place,
  resulting in modifications to the original plot object.
* `view_follow` now works with transformed scales.

# gganimate 1.0.0

* First CRAN release, featuring a complete rewrite... Too much stuff to put in
  a changelog
