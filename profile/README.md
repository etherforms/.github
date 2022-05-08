# EtherForms

Integrate web3 into any website in 3 steps, with little-to-zero coding skill requirements.

## Example

Simple donate button (with DAI) on Ethereum mainnet.

```html
<button
    type="button"
    data-web3-contract="0x6b175474e89094c44da98b954eedeac495271d0f"
    data-web3-function="transfer"
    data-web3-inputs="to:address,amount:uint256"
    data-web3-values="0xdeadbeefdeadbeefdeadbeefdeadbeefdeadbeef,"
>Transfer</button>
```

Or even simpler, using recipes:


```html
<button
    type="button"
    data-web3-recipe="{ipfs_hash_of_recipe}"
>Transfer</button>
```
