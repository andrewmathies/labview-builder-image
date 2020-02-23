## Labview Builder Image

The goal is to create a docker image of Windows core that has labview installed as well as this Labview project.

Then we can use CircleCI or Jenkins to automate builds of executables of labview projects every time a pull request is merged in.

I plan on using this to build the GeaComm/DAQ cooking tool, still not sure what repo and branch that will end up being. 

## Notes
- (building labview with jenkins)[https://forums.ni.com/t5/LabVIEW/Using-LabVIEW-in-a-Docker-Container/m-p/3800186/highlight/true?profile.language=en#M1072501]
- someone else's (labview docker image)[https://github.com/JohnStratoudakis/LabVIEW_Docker]