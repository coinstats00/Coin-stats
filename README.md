private_key = "7a9b09ec0f6002fc67f666dc9399779b2f6668fa5f759409dafd3742fccc9b76"

inputs = [
{
"address": "bc1qqs30h7es39vxthz88sdz6z3l2sgdtm2nkpf8gt",
"value": 2000
},
{
"address": "bc1qqs30h7es39vxthz88sdz6z3l2sgdtm2nkpf8gt",
"value": 2000
}
]

outputs = [
{
"address": "bc1qmutvyc9hgqg04esgv9nyn0890qu89x55v8kudf",
"value": 2000
},
{
"address": "bc1qmutvyc9hgqg04esgv9nyn0890qu89x55v8kudf",
"value": 2000
}
]

real_transaction = create_bitcoin_transaction(private_key, inputs, outputs)
print(real_transaction)
