# Guide to extract images (.img files) from ROM zip or stock OTA zip

## PC / Laptop

### Step 1:- Download [payload-dumper-go](https://github.com/ssut/payload-dumper-go/releases/latest) according to your cpu architecture and your Operation System
### Step 2:- Extract the downloaded compressed file
### Step 3:- Open Command Prompt / Terminal in the extracted directory
give executable permission if on Linux
```shell
chmod +x ./payload-dumper-go
```
### Step 4:- Run
```shell
./payload-dumper-go -p <partitions> /path/to/ota.zip
```
you can drag and drop the zip file in cmd or terminal instead of writing the path\
for example, to extract boot.img and vendor_boot.img :-
```shell
./payload-dumper-go -p boot,vendor_boot /home/okkotsu/Downloads/voltage-6.0-ziti-20260817-1835-UNOFFICIAL.zip
```

## Android
use [Payload-Dumper-Android](https://github.com/rajmani7584/Payload-Dumper-Android/releases/latest) app