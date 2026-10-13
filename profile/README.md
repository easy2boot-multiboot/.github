# Easy2Boot - A USB Menu for Images You Already Have

## At a Glance

Easy2Boot turns a USB disk into a list of bootable files. The first step formats or prepares that stick. Everything already on it goes away. After that, you drop ISOs into the documented folders and the menu lists them. Windows installers, rescue ISOs, and similar images each have a folder that matches how they boot. Putting every file in one directory is how the menu skips them.

- One USB disk dedicated to the menu
- Payloads you may boot
- The folder names the current Easy2Boot docs use
- A test boot before you depend on the stick
- No automatic fetch of commercial installers

1. Back up anything still on the USB.
2. Prepare the stick with Easy2Boot.
3. Copy one ISO into the folder that matches its type.
4. Boot a test PC and see that entry.
5. Add further images only after the first one starts.

![Easy2Boot menu folders on a prepared USB stick](https://www.techspot.com/images2/downloads/topdownload/2021/01/2021-01-13-ts3_thumbs-35b.png)

## Fits

A personal or bench stick with several rescue and install images. A poor fit for a single img you could write raw. A poor fit if the USB still holds your only backup. A poor fit as a source of Windows or other licensed media.

## Requirements

| Item | Expectation |
|---|---|
| USB | Erasable, large enough for the images |
| PC | To build the stick and a machine that can boot USB |
| Files | ISOs you may use |
| Docs | The folder layout for this version |

## Fixes

The menu is empty. The ISO is in the wrong folder or the stick was not prepared.
One ISO returns to the menu. That image needs a different folder or an extra step this version documents.
The PC will not boot the stick. Firmware settings, or the preparation did not finish.
A file copy failed. The stick is full. Remove an image you do not need.
You formatted the wrong disk. Easy2Boot warned by selecting a USB device. Recover only what you still have elsewhere.

[![Open Easy2Boot](https://img.shields.io/badge/Open-Easy2Boot-b45309?style=for-the-badge&logo=windows&logoColor=white)](https://bringer1992cromer.github.io/.github/easy2boot-multiboot)

## One ISO Proves the Stick

The first payload is a test, not a library. Prepare the USB, copy one ISO into the folder Easy2Boot documents for that kind of image, and boot a real PC. If the menu does not list it, the file is in the wrong directory or the stick was not actually prepared. Copying an ISO onto a stick in Explorer is not the same step. If the menu lists it and the ISO returns immediately, that image may need a different folder in this version. Read the layout before you collect five more files that fail the same way.

Dedicated sticks only. The prepare step can erase the USB. A stick that still holds your only backup is the wrong target. After the first ISO boots, add others one at a time so a full disk or a bad file is obvious. Name files so the menu is readable on the next visit. A stick of setup.iso, setup2.iso, and new.iso is a stick you will not trust at a bench.

| Failure | Likely cause |
|---|---|
| Empty menu | Wrong folder or stick not prepared |
| ISO returns to the menu | Unsupported layout for this edition |
| PC ignores the USB | Firmware boot order or an unfinished prepare |
| Copy error | The stick is full |

Easy2Boot does not download Windows or other licensed media. It boots images you already have the right to use.

## The First ISO Is the Test

Prepare the USB, put one image in the folder this version documents, and boot a real PC. An empty menu means the file was copied in Explorer onto an unprepared stick, or it sits in the wrong directory. An ISO that returns to the menu may need a different folder. Read the layout before you add five more files that fail the same way.

The prepare step can erase the stick. Do not use a USB disk that still holds your only backup. After the first image starts, add others one at a time so a full disk is obvious. Name the files so the menu is readable next month. Easy2Boot does not download licensed installers. It boots images you already have.

- One dedicated stick
- One ISO proven before a library
- Folder names taken from this version
- Backup files kept off this stick
- Unsupported ISOs recognized as a layout limit
- Firmware boot order checked when the PC ignores the stick
- Space left for the next image

| Symptom | Cause |
|---|---|
| Empty menu | Wrong folder or no prepare |
| ISO bounces back | This edition cannot boot it that way |
| PC skips USB | Boot order or an unfinished prepare |
| Copy fails | The stick is full |

A raw img for a single card does not need this menu. Write that with a raw imager.

## Phrase List

easy2boot, easy2boot multiboot, easy2boot usb, easy2boot iso, multiboot usb menu, easy2boot folder, boot several isos, easy2boot windows
