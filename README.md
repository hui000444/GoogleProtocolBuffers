# GoogleProtocolBuffers

How to intsall protocol buffer compiler
---

1. Download protocol buffer. Protocol buffer libs can be downloaded here. [Download protocol buffer](http://code.google.com/p/protobuf/downloads/list)  .
2. Unzip and Run these command to install:

```
$ sudo ./configure

$ sudo make

$ sudo make check

$ sudo make install

$ protoc --version
```

## How to compile .proto file
---

1. Run command:
   
   ```
   $ protoc -I=/Users/xxx/GoogleProtocolBuffers --java_out=/Users/xxx/GoogleProtocolBuffers/src/main/java /Users/xxx/GoogleProtocolBuffers/src/main/java/addressbook.proto 
   ```
2. Check `AddressBookProtos.java` generated 
