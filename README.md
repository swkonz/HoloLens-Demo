# HoloLens-Demo
HoloLens DirectX Demo Project
This repo contains A basic directX Hololens application that renders a cube into the user's field of view, and loads a DICOM file into memory. Loaded DICOM pixel data is not used.


### Dependencies
- Follow the instructions for installing the tools for HoloLens 2 Development: https://docs.microsoft.com/en-us/windows/mixed-reality/install-the-tools
	- This will require Windows 10, VS19, Windows 10 SDK, HoloLens 2 Emulator (Only for testing locally)
- Install DCMTK DICOM Toolkit: https://dicom.offis.de/dcmtk.php.en
	- For Windows, installation is easiest with choco: https://chocolatey.org/
	- Using choco: `choco install dcmtk`


### Details
- This project is essentially a duplicate of the starter directX project for hololens
- Details about this project structure can be found here: https://docs.microsoft.com/en-us/windows/mixed-reality/creating-a-holographic-directx-project
- Rendering details can be found here: https://docs.microsoft.com/en-us/windows/mixed-reality/rendering-in-directx