# Advanced Solidity - ERC-20 Token - Crowdsale
## By Franklin Vaca
<p>The program/code can be found in the KaseiCoin.sol and KaseiCoinCrowdsale.sol files located in the Starter Code folder. 
The code was witten on Solidity and the contracts were compiled and deployed using REMIX IDE. The contracts were tested using Ganache testnet and the addresses were connected via Metamask. The pictures presented below are located in the Evaluation_evidence folder. The screenshots display the contracts succesfully compiled, the deployment of the contracts and the transactions that were used to test the contracts. Screenshots from Ganache (transaction history) and Metamask indicate the interaction between the addresses and the contract.</p>
<p></p>

## **Step 1 _ KaseiCoin Token Contract**

*KaseiCoin Token Contract succesfully compiled* 

![image](Evaluation_evidence/1_kaseicoin_compiled_trans_1.PNG)

<p></p><br>

<p>No issues were found during compilation as indicated by the check mark and no error messages.</p>

## **Step 2 _ KaseiCoin Crowdsale Contract**

*KaseiCoin Crowdsale Contract succesfully compiled* 

![image](Evaluation_evidence/2_crowdsale_compiled_trans_1.PNG)

<p></p><br>

## **Step 3 _ KaseiCoin Deployer Contract**

*KaseiCoin Deployer Contract succesfully compiled* 

![image](Evaluation_evidence/3_deployer_compiled_trans_1.PNG)

<p></p><br>



<p>The crowdsale and deployer contracts were succesfully compiled and no error messages were found</p>

## **Step 4 _ Contracts deployed and tested in a Local Blockchain**
*Contract deployment:* 

![image](Evaluation_evidence/4_deploy_test_1.PNG)
<p></p><br>


<p>Token Kai (Symbol K) was created.</p>

*Metamask confirmation request and estimated gas fees for contract deployment:*


![image](Evaluation_evidence/4_deploy_test_2.PNG)
<p></p><br>


*Contract was succesfully deployed, contract now appears under the deployed contracts section:*


![image](Evaluation_evidence/4_deploy_test_3.PNG)
<p></p><br>



<p>0.03 ETH were taken from Ganache Account 1 Address 0xa98... was reduced from 100 ETH to 99.97 ETH.</p>

![image](Evaluation_evidence/4_deploy_test_4.PNG)
<p></p><br>

<p>Ganache's transaction history displays the contract creation and transaction hash:</p>

![image](Evaluation_evidence/4_deploy_test_5.PNG)
<p></p><br>


## **Test 1: Minting 8 tokens on 0xa98... address:**

*Using the mint function of the contract:* 

![image](Evaluation_evidence/4_deploy_test_6.PNG)
<p></p><br>


*Metamask confirmation and gas fees:* 

![image](Evaluation_evidence/4_deploy_test_7.PNG)
<p></p><br>



*New balance on the 0xa98... address:*

![image](Evaluation_evidence/4_deploy_test_8.PNG)
<p></p><br>


*Transaction registered on Ganache's transactions history:*

![image](Evaluation_evidence/4_deploy_test_8_1.PNG)
<p></p><br>


## **Test 2 (Minting on a different address): Minting 23 tokens on 0x85A... address:**

*Adding a new minter:* 

![image](Evaluation_evidence/4_deploy_test_8_2.PNG)
<p></p><br>


*Metamask confirmation and gas fees:* 

![image](Evaluation_evidence/4_deploy_test_8_3.PNG)
<p></p><br>


*Validating new minter was accepted:*

![image](Evaluation_evidence/4_deploy_test_8_4.PNG)
<p></p><br>

<p> Using the "isMinter" button: true, this confirms that the new address 0x85A... was accepted as a minter.</p>



*Using the mint function to mint 23 tokens:* 

![image](Evaluation_evidence/4_deploy_test_9.PNG)
<p></p><br>


*Metamask authorization request and estimated gas fees to proceed:*

![image](Evaluation_evidence/4_deploy_test_10.PNG)
<p></p><br>


*New balance on the 0x85A... address (23 tokens minted):*

![image](Evaluation_evidence/4_deploy_test_11.PNG)
<p></p><br>


*Transaction registered on Ganache's transactions history:*

![image](Evaluation_evidence/4_deploy_test_12.PNG)
<p></p><br>


## **Test 3 Total Supply of Kai tokens minted:**

*31 tokens = 23 tokens (first transaction) and 8 tokens (second transaction)*

![image](Evaluation_evidence/4_deploy_test_13.PNG)
<p></p><br>


## **Test 4 Transfering tokens minted:**

*Transfering 4 Kai tokens to 0x85A...*

![image](Evaluation_evidence/4_deploy_test_14.PNG)
<p></p><br>

*Metamask authorization request and estimated gas fees to proceed:*

![image](Evaluation_evidence/4_deploy_test_15.PNG)
<p></p><br>

*New balance on the 0x85A... address (27 tokens):*

![image](Evaluation_evidence/4_deploy_test_16.PNG)
<p></p><br>


*Transaction registered on Ganache's transactions history:*

![image](Evaluation_evidence/4_deploy_test_17.PNG)
<p></p><br>


*Total supply remains the same since the transaction was a transfer and no new tokens were minted:*

![image](Evaluation_evidence/4_deploy_test_18.PNG)
<p></p><br>


*The number of Kai tokens in 0xa98... address decreased from 8 (initially) to 4 after the transfer to 0x85A... :*

![image](Evaluation_evidence/4_deploy_test_19.PNG)
<p></p><br>


