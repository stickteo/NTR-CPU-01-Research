# NTR-CPU-01 PCB Scans

## Image Format

The images are scanned at 1200DPI. Reliable measurements can be made.

The PCB is *slightly* warped from the desoldering process. Otherwise it's *good enough* for tracing purposes.

Due to the large image sizes, images were exported via GIMP as JPEG with 95% quality. Around 20% size of PNG. Again, *good enough*. 

Some traces from the inner layers are missing... Partly due to the PCB warping and partly due to inexperience with sanding.

## PCB Deconstruction Process

The following process was taken:

1) Desoldered all components
2) Scanned L1-mask, L6-mask
3) Soldermask stripped
4) Scanned L1-nomask, L6-nomask
5) L1 sanded
6) L2 sanded (Power plane)
7) Scanned L3
8) L3 sanded
9) Scanned L4

## Image Editing

Minimal editing was undertook.

1) Fill in image gaps caused by scanner
  - Fixes geometry
  - Interpolated
2) Rotate
  - L6-nomask is mirrored
3) Align and crop

Rotation and interpolation was done with ImageMagick.

Alignment and cropping was done with GIMP.

## PCB Stackup

It is a 6 layer PCB.

* Silkscreen
* Soldermask
* Copper L1 (Top)
* Fiberglass
* Black layer (L2 adhesive?)
* Copper L2 (Power, Mostly ground?)
* Fiberglass
* Copper L3
* Fiberglass
* Copper L4
* Fiberglass
* Copper L5
* Black layer (L5 adhesive?)
* Fiberglass
* Copper L6 (Bottom)
* Soldermask
* Silkscreen

