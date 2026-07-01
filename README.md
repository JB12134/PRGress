# PRGress

PRGress is a simple web-based tool for building treadmill workout programs for the Livestrong LS8.0T in XML format. It lets you create a workout name, set total time, define segments, and export a `.prg` file that can be placed on a FAT32 USB drive in the `/LS/PROGRAMS/` folder.

## What this project includes

- A single-file web app: [PRGress.html](PRGress.html)
- Example workout files in the [DemoPrograms](DemoPrograms) folder

## How to use it

1. Open [PRGress.html](PRGress.html) in a web browser.
2. Enter a program name and total time.
3. Add workout segments with duration, incline, speed, and type.
4. Click “Generate XML” to create the program output.
5. Download or copy the generated XML and save it as a `.prg` file.
6. Copy the file to your USB drive under `/LS/PROGRAMS/`.

## Example programs

The [DemoPrograms](DemoPrograms) folder contains sample programs you can review and adapt.

## Reference credit

This project was inspired by the following reference sources:

- https://wiki.jmehan.com/display/KNOW/Treadmill+-+Livestrong+LS8.0T
- https://joe0.com/2014-09-06-how-to-create-your-own-workout-in-prg-xml-format-for-lifestrong-treadmill/

These sites were helpful in understanding the Livestrong treadmill program format and XML structure.
