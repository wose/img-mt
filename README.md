# img-mt

`img-mt` will be a tool to:
  - [ ] load huge image without using too much RAM using mipmaps
  - [ ] append lots of images to a big one to work on
  - [ ] post process images
  - [ ] use different look up tables
  - [ ] set image to world transformation
  - [ ] measure
    - [ ] distances
    - [ ] angles
    - [ ] diameters
  - [ ] save/load measurements
  - [ ] set points or regions of interest
    - [ ] name them
    - [ ] save/load them

## Building

```shell
% git clone --recursive -j4 https://github.com/wose/img-mt.git
% cd img-mt
% cargo build --release
% cargo run
```


