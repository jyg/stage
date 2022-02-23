# STAGE : multitouch browser-based GUI for PureData
Controlling PureData patches from browser with [Open Stage Control](https://openstagecontrol.ammd.net/) server.
![image](https://user-images.githubusercontent.com/1431894/154551869-8065fbe2-da76-4f52-9215-c1da3cfe7fc4.png)

**STAGE** is a series of abstractions for quickly creating an **OpenStageControl** .json file with GUI elements exported from an existing **PureData patch**. 

Once created, the script has to be executed by the OpenStageControl server, and enables the control of the PureData patch from a **browser-based client interface**, such as Chrome, Firefox, on any target platform (desktop, IPad, Android), via local networking.

## Requirements
* pd > 0.52
* iemguts externals lib

## Install
* clone or download github project
* copy (and rename) *stage* parent folder (and all its content) into your puredata externals folder
![image](https://user-images.githubusercontent.com/1431894/155305113-38f7d2cb-5cdb-470a-b609-f55e97aacc9d.png)

* in any pd patch, create a new [stage] object

![image](https://user-images.githubusercontent.com/1431894/155305485-2c28d239-0457-4c5b-bf05-f5ab8959ade9.png)

* read doc and tutorials

## Current supported and exported widgets :
* hsl / vsl
* bng
* tgl
* hradio / vradio
* comment
* array
* mob/lcd 
