# STAGE : multitouch browser-based GUI for PureData
Controlling PureData patches from browser with [Open Stage Control](https://openstagecontrol.ammd.net/) server.
![image](https://user-images.githubusercontent.com/1431894/154551869-8065fbe2-da76-4f52-9215-c1da3cfe7fc4.png)

**Warning : very alpha work in progress !**

**STAGE** is a series of abstractions for quickly creating an **OpenStageControl** .json file with GUI elements exported from an existing **PureData patch**. 

Once created, the script has to be executed by the OpenStageControl server, and enables the control of the PureData patch from a **browser-based client interface**, such as Chrome, Firefox, on any target platform (desktop, IPad, Android), via local networking.

## Requirements
* pd > 0.52
* iemguts externals lib

## Install
* You must preliminary have installed [Open Stage Control stuff](https://openstagecontrol.ammd.net/) .
* clone or download https://github.com/jyg/stage project
* copy (and rename) *stage* parent folder (and all its content) into your puredata externals folder

![image](https://user-images.githubusercontent.com/1431894/155305113-38f7d2cb-5cdb-470a-b609-f55e97aacc9d.png)

* in any pd patch, create a new [stage] object

![image](https://user-images.githubusercontent.com/1431894/155305485-2c28d239-0457-4c5b-bf05-f5ab8959ade9.png)

* read doc and tutorials

## Currently supported and exported widgets :
* hsl / vsl
* bng
* tgl
* nbx (number2  box)
* hradio / vradio
* comment
* array
* mob/lcd 

## Showcase
![image](https://user-images.githubusercontent.com/1431894/156921631-96b51600-0329-4f5b-a407-548cca0c7493.png)
