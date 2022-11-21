# xos-download


## Steps to download working thing of XOS

In case you are not able to run xos, use these steps



### Step 1
open terminal and go to a desired location

```
cd Downloads
```

### Step 2

Download xos

```
wget https://github.com/Siddhu2502/xos-download/raw/main/xos.gz
```

### Step 3

unzip it

```
tar -xvf xos.gz
```

### Step 4

Move the file to home directory so that its uniform for all

```
cp -r myxos-1/ ~/myxos
```

### Step 5

Install flex and bison

```
sudo apt install flex bison
```



Done :)
