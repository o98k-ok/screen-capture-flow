# screen-capture-flow

<p align="center"><img title="" src="assets/2022-03-18-10-49-21-image.png" alt="" width="169" ></p>

<h1 align="center">Screen-Capture-FLow</h1>
<div align="center">screen-capture and screen-record via alfred-workflow</div>

---

## Features

1. `command l`: captured image will stay in clipboard.

2. `command m`: captured image will save in env `$dest_dir`.

3. `command o`: recorded video will save in env `$dest_dir`.

## Installation

1. Download latest [Releases](https://github.com/o98k-ok/screen-capture-flow/releases) version.

2. Install it and complete the environment variable

   1. `dest_dir`: images/videos storage dir path.

   2. `pattern`: images filename shell command prefix., such as `date +%s`

## Usage

1. `command l` :

   1. select area

   2. press `space` and select a window

   ![](assets/command-l.gif)

2. `command m` same as `command l`

   ![](assets/command-m.gif)

3. `command o` select area and click `record`

## Todos

- [ ] `command o` support video pattern.

## Acknowledgement

1. [Xnip](https://xnipapp.com/) accompany me long time.

2. `screencapture` command in mac is amazing.
