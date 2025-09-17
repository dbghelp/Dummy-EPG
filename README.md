# Dummy-EPG
Dummy XML EPG for all time zones in the world

## Overview

This repository contains the Dummy XML EPG (Electronic Program Guide) for all time zones in the world. The EPG provides a schedule of the current and upcoming TV programs, enabling users to easily see what's on and plan their viewing.

Preview: https://dbghelp.github.io/epg.html?file=https://raw.githubusercontent.com/dbghelp/Dummy-EPG/refs/heads/main/dummy.xml

## Features

- XML formatted EPG for all time zones in the world
- Up-to-date information on channel programming
- Easy integration with various applications and services

## Usage

To use the EPG data, you can fetch the XML file from this repository and parse it in your application to display the program schedule.

In your M3U8 playlist, 

1. Change your url-tvg to "https://raw.githubusercontent.com/dbghelp/Dummy-EPG/refs/heads/main/dummy.xml":

```#EXTM3U url-tvg="https://raw.githubusercontent.com/dbghelp/Dummy-EPG/refs/heads/main/dummy.xml" refresh="3600"```

2. Change your tvg-id to the following for the respective channels:
  
|   tvg-id   |         Channel Name          |
|------------|-------------------------------|
| gmt-12     | GMT-12                        |
| gmt-11     | GMT-11                        |
| gmt-10     | GMT-10                        |
| gmt-9.5    | GMT-9.5                       |
| gmt-9      | GMT-9                         |
| gmt-8      | GMT-8                         |
| gmt-7      | GMT-7                         |
| gmt-6      | GMT-6                         |
| gmt-5      | GMT-5                         |
| gmt-4      | GMT-4                         |
| gmt-3.5    | GMT-3.5                       |
| gmt-3      | GMT-3                         |
| gmt-2.5    | GMT-2.5                       |
| gmt-2      | GMT-2                         |
| gmt-1      | GMT-1                         |
| gmt+0      | GMT+0                         |
| gmt+1      | GMT+1                         |
| gmt+2      | GMT+2                         |
| gmt+3      | GMT+3                         |
| gmt+3.5    | GMT+3.5                       |
| gmt+4      | GMT+4                         |
| gmt+4.5    | GMT+4.5                       |
| gmt+5      | GMT+5                         |
| gmt+5.5    | GMT+5.5                       |
| gmt+5.75   | GMT+5.75                      |
| gmt+6      | GMT+6                         |
| gmt+6.5    | GMT+6.5                       |
| gmt+7      | GMT+7                         |
| gmt+8      | GMT+8                         |
| gmt+8.75   | GMT+8.75                      |
| gmt+9      | GMT+9                         |
| gmt+9.5    | GMT+9.5                       |
| gmt+10     | GMT+10                        |
| gmt+10.5   | GMT+10.5                      |
| gmt+11     | GMT+11                        |
| gmt+12     | GMT+12                        |
| gmt+12.75  | GMT+12.75                     |
| gmt+13     | GMT+13                        |
| gmt+14     | GMT+14                        |
