## Solana Programming Flow:
###### 1. Client calls `entrypoint`
###### 2. `entrypoint` passess the information to processor
###### 3. `processor` uses `instruction` to decode `entrypoint's` `instruction_data`
###### 4. `processor` uses necessary function to satisfy instruction
###### 5. `processor`, using required functions changes `state` through ecoding or decoding specific `account` state
