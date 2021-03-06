# Handpose Application

See TP instructions in the _./TP_Instructions_ folder
Or [here](https://github.com/r-bbn/handpose_TP_SFFS/blob/master/TP_Instructions/TP.MD)

The purpose of this project is to control music thanks to hand gestures. Close hand : Music stops
Open hand : Music starts

It is based on the tensorflow model : handpose

## Get started

You need to get node and npm installed in your computer
Docker if you consider using docker to run the project

### Using http-server
First install project dependencies
```bash
npm install
```

Then run the application
```bash
cd ./app
npx http-server
```

The server is running on : http://localhost:8080

Be aware of disabling cache in Chrome : Dev tools/Network/Disable Cache

### Using docker

#### Build image & launch app :
```bash
cd docker
/bin/bash ./launch_app.sh
```

The server is running on : http://localhost:8080

Be aware of disabling cache in Chrome : Dev tools/Network/Disable Cache

#### Remove container and image
```bash
/bin/bash ./stop_app.sh
```