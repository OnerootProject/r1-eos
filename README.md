# r1-eos
EOS version of R1 Protocol is under development internal.
## Abstract
**Users** no need to deposit their assets in the **R1 contract** but just sign their off-chain order to the **Relayer** which will help to match and find the opposit order and finally the matched orders will be submitted by the **Relayer** . By this scheme we can benefit :
1. Relayer has the best matching performance as same as the CEX(Centralized Exchange);
2. Users keep their assets in their wallet with no need to trsut the contract;

## Features
* Asset No-Custodial 
* Free Trust & Security
* High Performance Matching
* Shared Liquidity

## Operate Procedure
1.User authorized contract has right of transfer tokens of eos system;
2.User sign his order(buy/sell token at a price) and submmit it to the relayer;
3.Relayer match the orders and commit it to the contract's trade method;
4. R1 contract will do this:
* Verify maker and taker's order info;
* Verify maker and taker's order not completed/canceled;
* Verify maker and taker's signature;
* Verify maker and taker's price matched;
* Exchange maker and tkaer's token at best price;
