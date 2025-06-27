Step 1: Open wallet. You may have only one profile (Profile 1). Choose the **Create a new profile** menu option
- Make note of your public account. Here it is `xQNTs` for Profile 1. This is your *staking address*.
  
![2](https://github.com/user-attachments/assets/f1a1fc3e-499e-4402-8b1f-919e0f1a03f6)


Step 2: Profile 2 has been created. Choose the **Back** menu option

![3](https://github.com/user-attachments/assets/0be34826-c4c8-4864-a352-c2e573059d80)



Step 3: You now have Profile 1 and Profile 2 in the wallet. Go into Profile 1
- Make note of the *new* public account. Here it is `267nJ` for Profile 2. This will be your *owner address*.
  
![4](https://github.com/user-attachments/assets/24ec5900-0911-4161-ad84-c31dee8c05cb)



From now all, *all* of your staking activity (stake, unstake, withdraw rewards, or transfering funds between wallets) will be done through the shielded account model.



Step 4*: Put your funds in the shielded account. (TODO: explain why optional)

![6](https://github.com/user-attachments/assets/79ef5db1-cb22-4a54-a5d0-15e363a9e769)

![5](https://github.com/user-attachments/assets/f4992c65-ead8-4073-9ead-67ebfbb3a469)



Step 5: Choose the **Stake** menu option

![7](https://github.com/user-attachments/assets/3c1a5c9f-128d-42be-8d30-c8b6350ac079)



Step 6: Choose the source of your funds. If following the guide strictly (step 4), your funds are in the shielded account, so choose the **Shielded** menu option.

![8](https://github.com/user-attachments/assets/fb034ed5-4f23-4e65-b74c-99264fd3f1ba)



Step 7: Since your wallet has two profiles, it now asks you which profile you want to be the *owner* of the stake. Choose your *owner address* from step 3 (it will be the second one in the list).
![9](https://github.com/user-attachments/assets/27525813-a2ed-4964-9136-c01426e44206)

![11](https://github.com/user-attachments/assets/cf25fd89-ad61-41a1-b286-a15990427547)


You are done. Check your **Stake Info** to verify your stake is active.

### You are only secure if this wallet is not on the same computer as the node itself.


## Bonus content

If you restore your wallet (e.g. with the seed phrase) and you do not generate profile 2, your unstake will fail.

![x3](https://github.com/user-attachments/assets/8206e5de-02ec-4ff3-a3d7-eb19c61602be)

Similarly, if a hacker steals the secrets of your *staking address* (Profile 1 public account) from your node, they:
 - Cannot unstake your funds
 - Cannot steal from your *shielded account*
 - Cannot generate Profile 2
