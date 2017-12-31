# bump2stl

Converts bump map stored in 16 bit png file into the stl mesh.

```man
usage: bump2stl [-h] [-H HIGH] [-S SIZE] input output

Converrt png bump map (intensity of pixel means high) to the stl mesh file.

positional arguments:
  input                 Input png file
  output                Output stl file

optional arguments:
  -h, --help            show this help message and exit
  -H HIGH, --high HIGH  Z coordinate of the maximum
  -S SIZE, --size SIZE  XY coordinate maximum
```