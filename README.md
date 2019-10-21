# Code Smells

This document gives actual examples of *code smells* -- characteristics of code that are not bugs, but may indicate an underlying problem in the implementation. It is based on the code smell list compiled at [Coding Horror](https://blog.codinghorror.com/code-smells/).

## Example (replace header title with the name of the code smell)

A brief summary of the code smell, described in plain language with a reason why it indicate a problem.

```{programming-language}
if( example == "good" )
{
  //do nothing
}
```
# SafeAlert/Buddii

This is a function that isnt dead code but is rather a temporary field since it is a work in progress. 

## Temporary Field (example of our code)

```{java}

private void setBlueThings(){ //THIS IS TEMPORARY YOU SONS OF BITCHES

   mMap.addCircle(new CircleOptions().center(new LatLng(39.726408, -121.847657))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.730534, -121.848798))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.728891, -121.848637))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.728735, -121.845895))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.729761, -121.843255))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.730822, -121.845217))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.728915, -121.846879))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
   mMap.addCircle(new CircleOptions().center(new LatLng(39.728071, -121.844249))
           .radius(10)
           .strokePattern(PATTERN_POLYLINE_DOTTED)
           .strokeColor(Color.BLUE)
           .fillColor(Color.CYAN));
}


