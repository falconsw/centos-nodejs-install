# CentOs 6.x - 7 Node.js install & Setup

<img src="https://github.com/falconsw/centos-nodejs-install/blob/master/nodejsinstagram.jpg"/>

## Provide ssh access and reach the main directory
```
cd ~
```

## Step 1 download node.js
```
wget https://nodejs.org/dist/v9.9.0/node-v9.9.0-linux-x64.tar.gz
```

## Step 2  decompression of compressed file
```
tar xvf node-v9.9.0-linux-x64.tar.gz
```

## Step 3 Move to nodejs folder
```
mv node-v9.9.0-linux-x64 nodejs
```

## Step 4 Create bin folder
```
mkdir ~/bin
```

## Step 5 Move the node directory to the bin folder
```
cp nodejs/bin/node ~/bin
```

## Step 6 Access bin directory
```
cd ~/bin
```

## Step 7 Running the npm
```
ln -s ../nodejs/lib/node_modules/npm/bin/npm-cli.js npm
```
