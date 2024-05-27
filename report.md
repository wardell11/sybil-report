This report contains 22 clusters, exceeding the character limit for issues. Later clusters and descriptions are moved to an external repository, which will remain unedited after submission.

Each cluster is independent with its own description and argumentation. Creating an issue per cluster is not possible due to GitHub’s spam flagging for numerous open issues.

# Methodology & Walkthrough
We collected 2.5 million CEX deposit addresses from Binance, Coinbase, Kucoin, Bybit, and OKX using explorers and Dune SQL. Filtered addresses received funds from at least 7 addresses interacting regularly with Layer Zero. Clusters of 7-300 addresses sharing the same CEX deposit address were formed using a script. An address had to link to at least 4 other cluster addresses to join. Clusters with fewer than 20 addresses were discarded.

# First Layer of Detection
Automated scripts identified clusters with a common CEX deposit address and interlinked addresses. This method, although robust, includes some false positives.

# Second Layer of Detection
Manually scanned each address to remove false positives and added on-chain arguments. This ensures cluster validity and minimizes false positives, using resources like LayerZero Scan, Dune, Debank, Arkham, and Etherscan.

# Activity Prior to Snapshot
Screened activities across 14 blockchains including Ethereum, Optimism, BSC, Polygon, Arbitrum, Gnosis, Linea, Scroll, Zksync, Moonbeam, Moonriver, FTM, Base, and Celo.

# Note on Arkham Diagrams
Links to Arkham diagrams are often missing as Arkham supports only 7 out of these 14 blockchains.

# Reward Address (If Eligible)
 (This is a fresh address).

# Table of Contents
Details

Clusters are independent, with descriptions including the shared CEX deposit address, an Arkham diagram, and the second layer of detection.

# Reported Addresses & Description
# CLUSTER 1
The addresses of the cluster share the same Binance deposit address 0x926e1F027351f3a216bA2789711aedE4544467B8. The rest are linked to numerous addresses of the cluster, multiple times.
```
0x220a6f204a8f8e6af9397c14ed019df08843ad3a
0x62bccddcf02f65bfc8b6a90e9678d9ba5689e174
0xabc67a49d7d75bd04fa1dae22cd4b8c4f796540a
0x7a4c8e3655d665f3e25ccd6b60b1b024629b3705
0x52b1e3ac180137a57231d0e562dd441c72d0f9e5
0x945057b10a2c1f4170178fa9d910241e4d17f546
0x75d25dfffff585b83b3f535b6ecad842fae3edd2
0xdc1ead8150beeeca0bc078881ccb4e1b4fd0abb6
0x0fe805304e49e993b2c59287000a2726330d2055
0xdaaa47da50c945bc97602cafe755cc2520ef2767
0x778023fdbde373f6dd13e39946412616ed119873
0x4e3e782053e560fdebd2be4a6c9a1f26c9a0faa4
0xbcccbf04cec0c7675955928bfa501f0535258c54
0xf3a82bc66f8b1397be2932c1cdc375153405a4a6
0x0539ea2214683632f51d0c995a204a1fd37f4b5a
0x3c320d49287e027967a1da048e901524de8f4666
0xd6e059dd8721083d766fab77efeb0191d89f6fcb
0xa4fafb2a712c8e7ff05128820ee1458495f9bfe8
0xc2e80d2715898d1dbedc729c0b69d589da7711c9
0x38da8174fe56b1efc6c9dd9ef4a03eabdc6e1596
0x88e62b22123754afc1f1095c8b939ba9fe0a941a
0x13dd1fb2e6bea092100876a6ff6fd31fa2e5aacf
0x9ab6ae3c3d080f613185e3aae8f1b7126ef4a43b
0xdca0f538d72b772d34a71eec383b135e5969f454
0x5878d75bf684e489ee6e7ea81213c68b56966154
0xa5762639ff1727c68b871dbac20d9bfb50e4615d
0xe4bea4d3e87299ada38bf6dc42fe9000eeceb6a6
0x6e06d26da609b8488ad20dfe3563047f7548246f
0x4e58bf6805d76b72447ccdc794db6d24316cf02c
0x3fd249d41d3f1444452329381aa07701cb754fcf
0x881f69aa89a41c69c7f44f07d9618c313e16ebc4
0xc0e459851ed330d6cba2ccd4f273fd8453bcf0a5
0x8aa3cbeef60630fec9f34642e29ee4aa1653b6da
0x25d45f33837122bbd9e70e46d072f1a0f8bb8d95
```
<img width="653" alt="Capture d’écran 2024-05-25 à 03 24 17" src="https://github.com/wardell11/sybil-report/assets/170775813/f2514301-8918-4360-9c95-d0b729273429">

The addresses all have the same on-chain activity. For example, their latest L0 interaction is exactly the same, the same dapps at the same time in the same order: Stargate, Orderly Network, Merkly.
<details>

<img width="1414" alt="Capture d’écran 2024-05-25 à 03 14 07" src="https://github.com/wardell11/sybil-report/assets/170775813/98799909-f674-4fc7-a5a0-896776d3351f">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 14 42" src="https://github.com/wardell11/sybil-report/assets/170775813/b549e9e3-9d94-4bd9-a5cb-0490cd09e7ca">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 15 08" src="https://github.com/wardell11/sybil-report/assets/170775813/9d51e9ac-8214-4995-86b8-ab31f3869a42">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 15 30" src="https://github.com/wardell11/sybil-report/assets/170775813/24e216f8-6116-4682-87a2-642ef408f90b">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 20 32" src="https://github.com/wardell11/sybil-report/assets/170775813/b28fe81b-3780-4411-9580-c53724dcedd2">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 20 53" src="https://github.com/wardell11/sybil-report/assets/170775813/3dddd3c5-7991-4c28-8b9e-baa7625c5713">
<img width="1440" alt="Capture d’écran 2024-05-25 à 03 21 15" src="https://github.com/wardell11/sybil-report/assets/170775813/7b12eec8-6bb2-4f54-b7bb-106533b66c0a">



</details>


etc...
The addresses also all have similar ENS.
The address share the same CEX deposit address, are part of a cluster with multiple links between one another, and have the same on-chain activity. This is a big scale sybil operation, probably the result of scripts.

# cluster 2

The first 12 addresses of the cluster share the same Binance deposit address 0x9649E21c2e4E16A3C836adcdada8e26Cd8Cc197d. The rest are linked to numerous addresses of the cluster, multiple times.
```
0xb5e9a9ca597f4bec5bfe34b4739cc8b2820675bd
0xd608f0c48411225b43e0c7a13021ae72d806c6a8
0x2dfb59b81d0cb5b7c984bcc2e262dc9fbee74298
0xbc84340c6329316f310679a7e4d48a8a6b65192e
0xc6c4f5063f8f6424cac6bce801d9a25edcc4a426
0xdae1a193639e2f113bdfe26a2cbc6b6e0e415fb8
0x6776a0e5b5566a5c1be3e6edeeb6824da0448f21
0x00a75ba3ea17b3c2782f0756022d1452c43ba7ca
0xb90dccdcc5694938dbf2cbadd809448c74e5bcec
0x42eee9dddd3302a19816554fab88fc560acc0efa
0xd5d3a68d149783a6e4ed3c14e78a9f74b8e6ee6a
0xecd40ff016c263a06ebf6958854fecadb2622818
0x7a3e5a5640213898c5c657cae9b45f826c0b4896
0x7713b0258952da63990a6b80bf2237878a9d1092
0xcc4dd02e63d391e803aaa0cb01e454ff111eaef7
0xa040b8bed171622a53a6181cbe9c11529d323652
0x193605b78873b63c653c18d3aa1295efe1bcf97d
0x7862a8f01a06f74a3d3111bad8f12fa1fc26921d
0x8762fc4b59d71c6d06dcfbd856fe1b60bd4e7564
0x0baf5dc796e95157411e0e3eaa4b6dd1d4b41537
```
The addresses share the same on-chain activity. They execute the same transaction at the same time in order to farm airdrops accross 20 wallets. For example, they all used Stargate to bridge and send token same amount of token (100$) to other cluster wallet addresses during the same day (many of them during June 25 2023) and stop using Layer 0 technology after that.

<details>

0xb5e9a9ca597f4bec5bfe34b4739cc8b2820675bd
<img width="974" alt="Capture d’écran 2024-05-27 à 21 59 13" src="https://github.com/wardell11/sybil-report/assets/170775813/71261448-aad9-4a7d-9b68-4afd4e2cf217">

0x6776a0e5b5566a5c1be3e6edeeb6824da0448f21
<img width="1033" alt="Capture d’écran 2024-05-27 à 22 12 06" src="https://github.com/wardell11/sybil-report/assets/170775813/5fa1d40b-a20c-430c-abfe-56157804ca6f">

0x2dfb59b81d0cb5b7c984bcc2e262dc9fbee74298
<img width="969" alt="Capture d’écran 2024-05-27 à 22 13 28" src="https://github.com/wardell11/sybil-report/assets/170775813/00337592-8c0b-4d54-a5cb-f7f05fe2d68a">

0xb90dccdcc5694938dbf2cbadd809448c74e5bcec
<img width="977" alt="Capture d’écran 2024-05-27 à 22 14 58" src="https://github.com/wardell11/sybil-report/assets/170775813/ff3f365f-56a8-480e-a235-ac6f1eebd343">

0xd608f0c48411225b43e0c7a13021ae72d806c6a8
<img width="972" alt="Capture d’écran 2024-05-27 à 22 15 49" src="https://github.com/wardell11/sybil-report/assets/170775813/389ded77-5839-4e00-a40a-ab765cb10941">

0x00a75ba3ea17b3c2782f0756022d1452c43ba7ca
<img width="968" alt="Capture d’écran 2024-05-27 à 22 17 03" src="https://github.com/wardell11/sybil-report/assets/170775813/0a2f87f0-124c-412e-a4b7-e0151fff859f">

0x42eee9dddd3302a19816554fab88fc560acc0efa
<img width="974" alt="Capture d’écran 2024-05-27 à 22 17 59" src="https://github.com/wardell11/sybil-report/assets/170775813/2c0f17a2-4db2-46b5-81c1-813781854039">


</details>


Same activity for all addresses of the cluster.

Also, you can see on Dune that all addresses have the same number of transactions with the same amount and were created 523 days ago.
<img width="956" alt="Capture d’écran 2024-05-27 à 22 20 13" src="https://github.com/wardell11/sybil-report/assets/170775813/fe0a514e-b481-42f6-ab5e-0177258b702e">

Same CEX deposit address, cluster, and exact same pattern of interaction with L0 with same amount to farm the airdrop. This is a clear sybil cluster.

# cluster 3
The first 12 addresses of the cluster share the same Binance deposit address 0x6ff197905601F6b8F59e3F71849e6a060D1dfd97. The rest are linked to numerous addresses of the cluster, multiple times.
```
0x1ded3c31ec30a1c651c7d1eca0f7db3ad76d15ef
0x1da5407a15e082e5f538e1c9f1bf3dcf812d1e15
0x6798a4be28e12b6346466f60f7e94c9becbf8fe2
0x8bea8c2f05917b493e1d1747cafff272f9545ea5
0x5b84cfb2660d510674a8b6ccd01659d2521fd5c1
0x925c8c407f1a3d988a06a45015256e49831a081b
0x8afe0a71682ece04af3b64e425c9e01f6712a6c4
0xd5565d3a05b2290e4f4cb9e2cc0e272f1a888b67
0xa8d66237c06b495e6597b4cb7cffc822b391ea2c
0x3450a682e5afba4e05d796584bc6cad9d3eeb99c
0xe2f51aac758d19b34877f44af1b8f998e1e265b1
0x9b02750d4c5348afbc52d83c3c3be8fc427fb879
0x25b3bcc2d83567561d1813bd4a3703bed5832254
0x0e030bad7f9e779ffc53d45c0748d6741ca567ad
0xeb6112a29cd11918885dddbd7f3db7404642ea38
0x9f41bff8678ad97ff99642e60aca011bbb88f60f
0x2ac2c30912bc44756411a6ab971f073d139819a9
0x9f38c4436a29e77e0a57cda343664f13d1c0fdf7
0xd1300820518f362180c747cbeeeb11e443bb8cdf
0x7a32c64265209562c004c8298e7ee0edcff07c83
```
<img width="605" alt="Capture d’écran 2024-05-27 à 23 41 46" src="https://github.com/wardell11/sybil-report/assets/170775813/da7ddd8e-39b0-4bf0-81b9-91a9fc460a5a">

The addresses have the same on-chain activity. For example, their L0 interaction follow the same pattern. They interact with the same dapps in the same order in the same timespans. 
As you can see : deposit 100$ + add liquidity 100$ on Stargate with all cluster addresses. 

<details>

0x8bea8c2f05917b493e1d1747cafff272f9545ea5
<img width="979" alt="Capture d’écran 2024-05-27 à 23 55 34" src="https://github.com/wardell11/sybil-report/assets/170775813/dbfb21cb-1fc0-4216-9d07-01a30471cc6b">

0x925c8c407f1a3d988a06a45015256e49831a081b
<img width="960" alt="Capture d’écran 2024-05-28 à 00 01 22" src="https://github.com/wardell11/sybil-report/assets/170775813/dae4330d-c0fe-4378-b252-e2edeb05b692">

0xa8d66237c06b495e6597b4cb7cffc822b391ea2c
<img width="971" alt="Capture d’écran 2024-05-28 à 00 02 47" src="https://github.com/wardell11/sybil-report/assets/170775813/e0760655-5bdc-473d-b26c-87750c4ebd24">

0x1da5407a15e082e5f538e1c9f1bf3dcf812d1e15
<img width="966" alt="Capture d’écran 2024-05-28 à 00 03 53" src="https://github.com/wardell11/sybil-report/assets/170775813/4efaf535-757c-4030-abc6-afb1c5040641">

0x1ded3c31ec30a1c651c7d1eca0f7db3ad76d15ef
<img width="957" alt="Capture d’écran 2024-05-28 à 00 04 55" src="https://github.com/wardell11/sybil-report/assets/170775813/050a0f17-02fa-48c5-933a-d7859ca250a0">

0x5b84cfb2660d510674a8b6ccd01659d2521fd5c1
<img width="964" alt="Capture d’écran 2024-05-28 à 00 06 47" src="https://github.com/wardell11/sybil-report/assets/170775813/e40d667d-bade-443c-af97-6bc4732710c6">




</details>


 We can see on Dune than all addresse have around 40-50 transactions with a total amount of 18.000$ and created 610 ago.
 <img width="964" alt="Capture d’écran 2024-05-28 à 00 06 47" src="https://github.com/wardell11/sybil-report/assets/170775813/8eea0fff-94fa-41bb-8101-536c9a43b231">

