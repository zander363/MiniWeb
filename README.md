# MiniWeb
this is a mini web build by *flask*
to evaluate the security of flow.
We evaluate the flow by
1. Distinguish Malware from Benign one.
2. Multiclass Classification to classify different application

## Environment
- *Ubuntu==16.04* 
- *python==3.5.2*

## Dependency
- *Flask==1.0.2*
- Other packages version are specified in requirements.txt

## Install
`./install.sh`

## Usage
`python3 server.py`
Our server will be run on localhost:5000

## Feature Extraction Tools
- [CICFlowMeter](https://github.com/ISCX/CICFlowMeter)
- [joy](https://github.com/cisco/joy)

## docker
you can also use docker to build and run our program.
`docker build --rm -t miniweb .
 docker run -p 5000:5000 miniweb`


