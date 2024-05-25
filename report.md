This report contains 22 clusters, exceeding the character limit for issues. Later clusters and descriptions are moved to an external repository, which will remain unedited after submission.

Each cluster is independent with its own description and argumentation. Creating an issue per cluster is not possible due to GitHub’s spam flagging for numerous open issues.

# Methodology & Walkthrough
We collected 2.5 million CEX deposit addresses from Binance, Coinbase, Kucoin, Bybit, and OKX using explorers and Dune SQL. Filtered addresses received funds from at least 7 addresses interacting regularly with Layer Zero. Clusters of 7-300 addresses sharing the same CEX deposit address were formed using a script. An address had to link to at least 4 other cluster addresses to join. Clusters with fewer than 20 addresses were discarded.

First Layer of Detection
Automated scripts identified clusters with a common CEX deposit address and interlinked addresses. This method, although robust, includes some false positives.

Second Layer of Detection
Manually scanned each address to remove false positives and added on-chain arguments. This ensures cluster validity and minimizes false positives, using resources like LayerZero Scan, Dune, Debank, Arkham, and Etherscan.

Activity Prior to Snapshot
Screened activities across 14 blockchains including Ethereum, Optimism, BSC, Polygon, Arbitrum, Gnosis, Linea, Scroll, Zksync, Moonbeam, Moonriver, FTM, Base, and Celo.

Note on Arkham Diagrams
Links to Arkham diagrams are often missing as Arkham supports only 7 out of these 14 blockchains.

Reward Address (If Eligible)
 (This is a fresh address).

Table of Contents
Details

Clusters are independent, with descriptions including the shared CEX deposit address, an Arkham diagram, and the second layer of detection.

Reported Addresses & Description
CLUSTER 1
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






