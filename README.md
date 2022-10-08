
# twilight

twilight is an application built using the Cosmos SDK for testing and educational purposes.  It was made like this:

```bash
git clone https://github.com/cosmos/cosmos-sdk
mkdir twilight
cp -r cosmos-sdk/simapp/* twilight
```

* modify the go module path in go.mod
* modify the name of simd folder like: 

```bash
mv simd twilight
```

So, there's a chain with sdk 47 now.  The goal of twilight is to demonstrate a working chain using sdk 47 with ibc-go, cosmwasm, and the interchain accounts demo controller app. 
