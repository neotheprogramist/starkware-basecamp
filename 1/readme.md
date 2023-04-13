# compile cairo code
```shell
starknet-compile src/example.cairo sierra/example.json
```


# create account
```shell
starknet new_account --account v0.11.0.2-homework
```
## account address
0x02343bc23dd6b9d71e718d7ca8947e01bacca8053ce5aaf22b240fe0ac68b7c4
## public key
0x052285971a2f0a1bf6f8d85260bce2dc7ad478616d8cef423f3bca16098ac2a2


# deploy account
```shell
starknet deploy_account --account v0.11.0.2-homework
```
## contract address
0x02343bc23dd6b9d71e718d7ca8947e01bacca8053ce5aaf22b240fe0ac68b7c4
## transaction hash
0xdb8cf69eb526b20d9504e8a6c957c349d4b52737efa73f2d0984c53ea2250


# declare class
```shell
starknet declare --contract sierra/example.json --account v0.11.0.2-homework
```
Already declared
## class hash
0x9b09ce076e1789d2901b83b27f88b9dfdc5d8952ee694f0ad6416640839af7


# deploy contract
```shell
starknet deploy --class_hash 0x9b09ce076e1789d2901b83b27f88b9dfdc5d8952ee694f0ad6416640839af7 --account v0.11.0.2-homework
```
## contract address
0x0062650a137258cb3c4f130ffdc1f5ecfba49eed73a23117d37da4370329333a
## transaction hash
0x63b4f14fb87c061221212936485cc873d7c209fdcaccea22f43617d86260960
