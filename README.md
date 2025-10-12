![BedrockCoin Logo](BedrockCoin.png)

**BedrockCoin (BRK)** is a secure, decentralized cryptocurrency built on **Scrypt Proof-of-Work**, designed for long-term stability and fair distribution. With a fixed supply and predictable emission schedule, BRK offers a reliable foundation for digital transactions and value storage.

---

📊 Technical Specifications

| Parameter                     | Value                     |
|------------------------------|---------------------------|
| **Algorithm**                | Scrypt PoW                |
| **Coin Name**                | BedrockCoin               |
| **Ticker**                   | BRK                       |
| **Block Time**               | ~12 minutes               |
| **Difficulty Adjustment**    | Every 120 minutes (10 blocks) |
| **Block Reward**             | 2 BRK                     |
| **Total Supply**             | 7,460,000 BRK             |
| **Halving Interval**         | Every 1,865,000 blocks    |
| **P2P Port**                 | 24732                     |
| **RPC Port**                 | 24731                     |
| **Mainnet Address Prefix**   | `B`                       |
| **Testnet Address Prefix**   | `P`                       |
| **Transaction Confirmations**| 3 blocks                  |

> 💡 All consensus and network parameters are defined in [`src/chainparams.cpp`](src/chainparams.cpp).

---

🚀 Build from Source

Linux (Ubuntu/Debian)
```bash
# Install dependencies
sudo apt update
sudo apt install build-essential libtool autotools-dev automake pkg-config bsdmainutils python3 libssl-dev libevent-dev libboost-system-dev libboost-filesystem-dev libboost-chrono-dev libboost-test-dev libboost-thread-dev

# Clone and build
git clone https://github.com/bedrockcoin/BedrockCoin-BRK---Official-Source.git
cd BedrockCoin-BRK---Official-Source
./autogen.sh
./configure
make
```

macOS (with Homebrew)
```bash
brew install automake berkeley-db4 libtool boost miniupnpc openssl pkg-config python3 qt5
git clone https://github.com/bedrockcoin/BedrockCoin-BRK---Official-Source.git
cd BedrockCoin-BRK---Official-Source
./autogen.sh
./configure
make
```

> 📌 **Binaries**:  
> - Daemon: `src/bedrockcoind`  
> - CLI Tool: `src/bedrockcoin-cli`

---

📦 Wallet Setup

- **Default Data Directory**:  
  - Linux: `~/.bedrockcoin/`  
  - Windows: `%APPDATA%\BedrockCoin\`  
  - macOS: `~/Library/Application Support/BedrockCoin/`

- **Example `bedrockcoin.conf`**:
  ```ini
  rpcuser=your_username
  rpcpassword=your_strong_password
  server=1
  daemon=1
  ```

> 🔒 **Never share your `wallet.dat` or private keys.**

---

🔗 Official Resources

- **Website**: [https://thebedrockcoin.web.app](https://thebedrockcoin.web.app)  
- **Block Explorer**: [http://explorebrk.duckdns.org:3001](http://explorebrk.duckdns.org:3001)  
- **Discord**: [Join Community](https://discord.gg/VwN7yZr8)  
- **Telegram**: [@BedrockCoinGroup](https://t.me/bedrockcoinoficial)  

> ⚠️ Twitter is currently unavailable. Follow updates via Discord or Telegram.

---

🤝 Contributing

We welcome community contributions!  
Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting pull requests.

- Report issues via [GitHub Issues](https://github.com/bedrockcoin/BedrockCoin-BRK---Official-Source/issues)
- Follow the [Bitcoin Core coding style](https://github.com/bitcoin/bitcoin/blob/master/doc/developer-notes.md)

---

## 📜 License

BedrockCoin is open-source software released under the **[MIT License](COPYING)**.  
Transparency, security, and decentralization are at the core of our mission.