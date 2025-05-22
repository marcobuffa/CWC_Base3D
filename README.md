# CWC_Base3D

## A very basic 3D Custom Web Control (CWC) to show how stuff works with WinCC Unified & three.js

![A 3D "3D" Monument]({00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}/assets/3d.png)

## ToDo:

- [x] Get requests by customers
- [x] Get requests by colleagues
- [x] Find a timeslot
- [x] Write basic code
- [x] Debug
- [x] Test on WinCC Unified
- [ ] Add features (more interaction with the operator)

## How to create a CWC from this stuff:

1. Download/pull/whatever the code
2. cd in the **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}** folder
3. Create **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}.zip** file with the **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}** folder content
> [!IMPORTANT]
> Do not include the **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}** folder itself as root folder in the file zip!
4. Copy the **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}.zip** file in **C:\Program Files\Siemens\Automation\Portal Vxx\Data\Hmi\CustomControls** folder
5. (Re)start TIA Portal
6. Drag your new 3D CWC from the **My Controls** right side pane in a WinCC Unified screen
7. Enjoy

## How to directly download this CWC (if you are in a hurry):
1. Download from [here](build/{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}.zip)
2. Copy the **{00bd2ed4-56cf-49ef-aeac-6c7454f5abd7}.zip** file in **C:\Program Files\Siemens\Automation\Portal Vxx\Data\Hmi\CustomControls** folder
3. (Re)start TIA Portal
4. Drag your new 3D CWC from the **My Controls** right side pane in a WinCC Unified screen
5. Enjoy

## What's the real meaning of this code?
This CWC (Custom Web Control) is **just** intended to show how to integrate a mechanical 3D model in WinCC Unified using [three.js](https://threejs.org/) powerful JS library. Please, refer to [three.js documentation](https://threejs.org/manual/#en/creating-a-scene) for any three.js related issue.