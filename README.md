# Solana Co Learn

## Solana 入门

Rust 速览、Solana Local Node、Solana CLI Tools、Network Wallet 交互

### 1. Rust 速览

🔗 [Rust 共学文档](https://github.com/CreatorsDAO/rust-co-learn/blob/main/rust-co-learn.md)

- **环境安装**
- **Cargo 使用配置**
- **Rust 语法基础**
  - 变量（可变量、类型、复合类型、引用、集合、结构体、枚举）
  - 函数、闭包
  - 泛型
  - 控制流
  - 模式匹配
  - 注释

### 2. Solana Local Node

🔗 [CLI 安装指南](https://solana.com/zh/developers/guides/getstarted/setup-local-development)

- **CLI 安装**
- **操作指南**
  - 初始化账户，秘钥对，获得 airdrop
  - 导入导出秘钥，切换网络
  - 启动本地节点，监控 logs

### 3. Network Wallet交互

- **浏览器扩展安装**
  - Backpack
  - Phantom
- **账户操作**
  - 初始化账户，导入导出秘钥
  - 网络浏览器查看账户、交易

## Solana Native

使用Solana Native开发、读写 Account Data、Account 数据传输序列化，数据检查（TypeScript SDK基本使用）

### 1. Solana Native

[Hello world](https://solana.com/zh/developers/guides/getstarted/local-rust-hello-world)

- 编译合约、部署合约、调用合约
- 区块浏览器查看合约

### 2. Account 数据基本读写

[实例实现数据读写](https://creatorsdao.github.io/solana-co-learn/Solana-Co-Learn/module3/native-solana-development/build-a-movie-review-program/)

[状态管理和序列化](https://creatorsdao.github.io/solana-co-learn/Solana-Co-Learn/module3/native-solana-development/state-management/)

- 合约读取数据
- 合约使用PDA 账户
- 迭代用户
- 序列化反序列化数据

### 3. TypeScript SDK

[https://solana.com/docs/clients/javascript](https://solana.com/docs/clients/javascript)

- 生成账户
- 获取 airdrop
- 读取account 数据
- 通过指令调用合约

## Anchor Framework

- **合约部分**
- **前端部分**
  - 构建完整的基于Anchor的Solana应用

## 4. Solana 进阶

- **PDA 生命周期**
- **CPI 调用**
- **SPL Token**
- **NFT**
