# Sunrise

A simple C++ library for calculating the time of sunrise and sunset, given a
latitude, longitude and date.

## Usage

There is a simple example in `main.cpp`

```c++
int main(int argc, char * argv[])
{
  Sunrise sr;

  printf("====== %0.5fN, %0.5fW ======\n", sr.getLatitude(), sr.getLongitude());

  printf("Sunrise: "); sr.print_time(sr.get_sunrise());
  printf("Sunset: "); sr.print_time(sr.get_sunset());

  return 0;
}
```

## License

This is licensed under an MIT license.

```
Copyright (C) 2015 Simon Cooksey

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
