# Workshop 

1. A safe wallet tx was given and we have to decode the TX hash, when connected to MM
2. The decoding was done using the folowing command 
3. There will be a blog, on these steps soon 

```rs 
cast calldata-decode "approve(address, uint256)" 0x095ea7b3000000000000000000000000dd13e55209fd76afe204dbda4007c227904f0a810000000000000000000000000
000000000000000000000000000000000000001

> 0xdd13E55209Fd76AfE204dBda4007C227904f0a81
> 1
```
- Here the `1` means that 1 wei was approved
- 