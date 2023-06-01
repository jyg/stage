# STAGE : multitouch browser-based GUI for PureData
Controlling PureData patches from browser with [Open Stage Control](https://openstagecontrol.ammd.net/) server.
![image](https://user-images.githubusercontent.com/1431894/154551869-8065fbe2-da76-4f52-9215-c1da3cfe7fc4.png)


https://github.com/jyg/stage/assets/1431894/e0873c08-9b2b-4480-9d8b-f8c90cd0a6c4


**Warning : very alpha work in progress !**

**STAGE** is a series of abstractions for quickly creating an **OpenStageControl** .json file with GUI elements exported from an existing **PureData patch**. 

Once created, the script has to be executed by the OpenStageControl server, and enables the control of the PureData patch from a **browser-based client interface**, such as Chrome, Firefox, on any target platform (desktop, IPad, Android), via local networking.

## Requirements
* pd > 0.52
* **iemguts** + **iemlib** externals libs

## Install
* You must preliminary have installed [Open Stage Control stuff](https://openstagecontrol.ammd.net/) .
* clone or download https://github.com/jyg/stage project
* copy (and rename) *stage* parent folder (and all its content) into your puredata externals folder

![image](https://user-images.githubusercontent.com/1431894/155305113-38f7d2cb-5cdb-470a-b609-f55e97aacc9d.png)

* in any pd patch, create a new [stage] object

![image](https://user-images.githubusercontent.com/1431894/155305485-2c28d239-0457-4c5b-bf05-f5ab8959ade9.png)

* you get the following abstraction

![image](https://user-images.githubusercontent.com/1431894/158797114-9f49b79d-9212-4494-83c0-4126d8647d63.png)

* if you click on green button ("network_settings"), you get the network configuration window.

![image](https://user-images.githubusercontent.com/1431894/158797367-466d1bf1-b002-40ec-863c-7ab6ac083ccb.png)

* compare the port settings with the corresponding properties values in Open Stage Control server : 

![image](https://user-images.githubusercontent.com/1431894/158798624-e4e03641-224c-47d5-901d-e3eea94c4d8e.png)
![image](https://user-images.githubusercontent.com/1431894/158798647-5432ec9e-3c0e-4fcf-9f01-b10a88d6f185.png)

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
## To do list
* canvas
* symbol box
* openpanel and savepanel abstractions for file browsing from O.S.C.

## Showcase
* MobMupic : UPIC-style sequencer
![image](https://user-images.githubusercontent.com/1431894/156921631-96b51600-0329-4f5b-a407-548cca0c7493.png)
![image](https://user-images.githubusercontent.com/1431894/156921761-6cc8ff25-da6c-4ae5-8875-c84f9579f52c.png)

