---
date: 2020-01-31T10:15:18-04:36
description: "Here I wrote a code where I mine three blocks and add them to the Blockchain"
featured_image: "/images/Blockchain/BlockchainMining/BlockchainMining.JPG"
title: "Blockchain: Mining"
---

* Created a **BLOCK Class** and a **Mine** algorithm.
* The **BLOCKS** are encrypted with the **SHA256** hash function and each block has it's difficulty increased by 1 starting from 4 zeros.
* **Mining** will loop through all the blocks guessing their **Hash** and will stop when the guessed hash starts with the number of zeros previously set by the Mining Function, after that it will attach the Block to the **Blockchain**. The function is programmed to fail if the **Nonce** reaches 1 × 10⁹ trials.
* For each **successfully mined** Block, the Mine function will output the time needed to mine the block, the number of trials and the mined hash.
* At the very end, the Blockchain is printed.<p>.
{{< figure src="/images/Blockchain/BlockchainMining/BlockchainMining.JPG" >}}
[Link to GitHub Repository](https://github.com/Relor91/Blockchain/tree/main/Blockchain%20Mining)
