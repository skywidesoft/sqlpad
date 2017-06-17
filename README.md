Docker image - SqlPad
---------------------

### Details
- Node: Boron
- Sqlpad: 2.2.0

### Build image
    docker build -t skywidesoft/sqlpad .

### Push image
    docker push skywidesoft/sqlpad

### Tag image
    docker tag [image-id] skywidesoft/sqlpad:2.2.0
    docker push skywidesoft/sqlpad:2.2.0

### Run container

#### Standalone
    docker run --name sqlpad -d -p 5000:3000 skywidesoft/sqlpad:2.2.0

#### Connect a network
    docker run --name sqlpad -d --network [network-name] -p 5000:3000 skywidesoft/sqlpad:2.2.0
