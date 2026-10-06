
Works on ubuntu

69 rather than 72 because xml2rfc adds 2 spaces in front of sourcecode

```shell
$ ./rfcfold.sh -s 1 -c 69 -i usage-example-xml.xml -o wrapped.xml
$ ./rfcfold.sh -s 1 -c 69 -i rpc.xml -o wrapped.xml
$ ./rfcfold.sh -s 1 -c 69 -i rpc-reply.xml -o wrapped.xml
```
