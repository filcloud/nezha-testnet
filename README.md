<p align="center">
  <a href="https://github.com/filcloud/nezha-testnet">
    <img alt="Nezha" src="./images/nezha.jpg">
  </a>
</p>

# nezha-testnet

Nezha (哪吒) Testnet is a developer-friendly and miner-friendly Filecoin community-driven testnet maintained by a group of Filecoin community developers/miners.

## Why another testnet?

Filecoin is under active development leaded by Protocol Labs, and now it has two implementations, i.e., [go-filecoin](https://github.com/filecoin-project/go-filecoin) and [lotus](https://github.com/filecoin-project/lotus). The devnet of go-filecoin was attacked many times and was in a state of paralysis. A group of talented developers from Protocol Labs are refactoring many of the key modules of go-filecoin, regardless of fixing the devnet. Although the new lotus devnet has just been released not long ago, maintaining the stable running of it is still not and should not be the top primary task of Protocol Labs. As we all know, other well-known blockchains, such as Bitcoin and Ethereum, also have several testnets suitable for different test scenarios. Therefore, the majority Filecoin community developers or miners have sufficient motivation and obligation to build the first community-driven testnet, to facilitate developers to test features and miners to evaluate mining hardware.

Nezha testnet will be a stable Filecoin test network for developers and miners, carefully maintained by community developers to ensure security and rapid repair after being attacked. It will be based on the [lotus](https://github.com/filecoin-project/lotus) implementation, and synchronize with the latest features as early as possible, and provide compiled binary programs with configured parameters, as well as high-speed downloadable proof parameter files and fast chain-syncing bootstrap P2P nodes (especially important for Chinese developers and miners). It is also hoped that by participating in the Nezha testnet, it is possible to form a community for sharing testing experience by community developers or miners. We believe that Nezha is a very useful contribution to the launch of the upcoming Filecoin mainnet next year 2020.

Filecoin 正在协议实验室领导下紧张开发中，目前拥有两个实现，分布是 [go-filecoin](https://github.com/filecoin-project/go-filecoin) 和 [lotus](https://github.com/filecoin-project/lotus)。go-filecoin 的开发者测试网被攻击了好多次，处于瘫痪状态。协议实验室的一群天才开发者正在重构 go-filecoin 的很多关键模块，无暇顾及开发者测试网的修复。虽然新的 lotus 开发者测试网不久前刚释出，但维护测试网的稳定运行依然不是也不应该是 Protocol Labs 的当务之急。众所周知，其他知名区块链，比如比特币和以太坊，也拥有多条适合不同测试场景的测试网。所以广大的 Filecoin 社区开发者或矿工有足够的动机和义务，构建社区驱动的第一条测试网，以方便开发者测试功能和矿工评测矿机。

哪吒测试网将是对开发者和矿工友好的稳定运行测试网，由社区开发者精心维护，保障安全和被攻击后的快速修复。它将基于 lotus 的实现，尽可能地同步最新的功能特性，并提供已编译好且配置好参数的二进制程序，以及提供可高速下载的参数文件和可快速接入的 P2P 启动节点（对于中国开发者和矿工而言非常重要）。也希望借着参与哪吒测试网的机会，能够组建一个可供广大社区开发者或矿工交流测试经验或心得的社群。我们相信，哪吒测试网对于2020年即将到来的 Filecoin 主网启动，是一个非常有益的贡献。

## Why named as Nezha?

哪吒（Nezha）是莲花（Lotus）化身，出自于中国古典神话小说《封神演义》和《西游记》。由两朵莲花和三片荷叶组成，其中包含了一枚存有魂魄的金丹，乃太乙真人将哪吒起死回生复活而所创的宿体。在西游版本中为如来佛祖采取荷藕为哪吒做身。

## Requirements

- Hardware: at least with 4 CPUs, 16GB memory, 500GB disk
- OS: Ubuntu 18.04 or CentOS 7, etc.

## Join Nezha Testnet

Download binary:

Start daemon:

Create wallet address and grab some FILs from faucet:

Initialize storage miner and start mining:

Continuously generate random pieces:

After a while, show your mining status:

## Maintainers

- [@RideWindX](https://github.com/ridewindx)
- [@Frank](https://github.com/deaswang)

## Contributing

Feel free to dive in! [Open an issue](https://github.com/filcloud/nezha-testnet/issues/new) or submit PRs.

### Contributors

This project exists thanks to all the [people](https://github.com/filcloud/nezha-testnet/graphs/contributors) who contribute. 

## License

[MIT](LICENSE) © FilCloud
