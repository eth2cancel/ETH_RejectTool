# ETH_RejectTool
eth交易撤销器:

老是有萌新说eth交易卡了。。。有人推荐用myetherwallet导入私钥再用卡死交易的nonce发起一笔0eth的self交易；

但是myether经常被dns劫持，在上面导入私钥或助记词是件很危险的事。

本人就好心写了一个撤销器，原理是一样的。代码开源，web3轻钱包用infura节点，发送rawTx交易保证私钥安全。
