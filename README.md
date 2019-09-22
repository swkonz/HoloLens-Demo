# HoloLens-Demo
HoloLens DirectX Demo Project
This repo contains A basic directX Hololens application that renders a cube into the user's field of view


### Dependencies
- Follow the instructions for installing the tools for HoloLens 2 Development: https://docs.microsoft.com/en-us/windows/mixed-reality/install-the-tools
	- This will require Windows 10, VS19, Windows 10 SDK, HoloLens 2 Emulator (Only for testing locally)


### Details
- This project is a duplicate of the starter directX project for hololens with some tweaking for reading a DICOM Image using DCMTK
- Details about this project structure can be found here: https://docs.microsoft.com/en-us/windows/mixed-reality/creating-a-holographic-directx-project
- Rendering details can be found here: https://docs.microsoft.com/en-us/windows/mixed-reality/rendering-in-directx

### DICOM Processing Library review
- I looked at using DCMTK and Imebra as libraries for reading DICOM files within the directX project.
- I did prototyping with the DCMTK python bindings to do a bit more research on the file formatting.
- DCMTK: https://support.dcmtk.org/docs/
- Imebra: https://imebra.com/