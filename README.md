<div align="center">

<img src="banner.svg" alt="ReweCoin" width="100%">

<br>

![MAINNET](https://img.shields.io/badge/MAINNET-LIVE-39ff14?style=for-the-badge&labelColor=0a0000)
![MINING](https://img.shields.io/badge/MINING_POOL-ACTIVE-ffd700?style=for-the-badge&labelColor=0a0000)
![EXPLORER](https://img.shields.io/badge/EXPLORER-ONLINE-ffd700?style=for-the-badge&labelColor=0a0000)
![ALGO](https://img.shields.io/badge/ALGORITHM-EQUIHASH-e10600?style=for-the-badge&labelColor=0a0000)

<br>

**An independent Equihash blockchain with its own wallet, explorer and mining pool.**

<br>

<a href="https://rewecoin.com/"><img src="btn-website.svg" width="170" alt="Website"></a> <a href="https://wallet.rewecoin.com/"><img src="btn-wallet.svg" width="170" alt="Wallet"></a> <a href="https://explorer.rewecoin.com/"><img src="btn-explorer.svg" width="170" alt="Explorer"></a> <a href="https://pool.rewecoin.com/"><img src="btn-pool.svg" width="170" alt="Mining Pool"></a>

</div>

<br>

<img src="circuit-board.svg" width="100%" alt="">

> [!NOTE]
> **Early-stage network:** hashrate is currently very low (around 1 Sol/s), so new miners have a real impact.

<img src="divider.svg" width="100%" alt="">

## Network status

| Component | Status |
|:---|:---:|
| Mainnet | <img src="led.svg" width="16" height="16" alt="live"> Live |
| Mining pool | <img src="led.svg" width="16" height="16" alt="live"> Active |
| Explorer | <img src="led.svg" width="16" height="16" alt="live"> Online |
| Wallet | <img src="led.svg" width="16" height="16" alt="live"> Online |
| Seed nodes | <img src="led.svg" width="16" height="16" alt="live"> Live |
| Worm Shield | <img src="led.svg" width="16" height="16" alt="live"> Live |

<img src="divider.svg" width="100%" alt="">

## Quick start

<img src="flow.svg" width="100%" alt="Quick start: create wallet, create mining address, start miner, pool, block found, 100 confirmations, payout every 10 minutes">

<img src="divider.svg" width="100%" alt="">

### Step 1: create your wallet and mining address

1. Open https://wallet.rewecoin.com and create (or open) your wallet.
2. Back up your recovery phrase offline. Anyone who has it can take your coins, and if you lose it you lose access.
3. Go to https://wallet.rewecoin.com/mining.html and click **Create mining address**.
4. Copy the new address from the "Mining addresses" table. Use it as your username in the miner.
5. Track found blocks, pending rewards and confirmed rewards on the same Mining page.

<img src="divider.svg" width="100%" alt="">

<div align="center">

## HOW TO MINE

![Server](https://img.shields.io/badge/SERVER-178.104.208.90-0a0000?style=for-the-badge&labelColor=ffd700&color=0a0000)
![varDiff](https://img.shields.io/badge/PORT_3092-AUTO_DIFFICULTY-e10600?style=for-the-badge&labelColor=0a0000)
![Fixed](https://img.shields.io/badge/PORT_3093-FIXED_DIFFICULTY-ffd700?style=for-the-badge&labelColor=0a0000)

</div>

<br>

| Setting | Value |
|:---|:---|
| **Server** | `178.104.208.90` |
| **Port** | `3092` (auto difficulty) or `3093` (fixed difficulty) |
| **Username** | your ReweCoin wallet address (optionally add a worker name: `ADDRESS.worker1`) |
| **Password** | `x` |
| **Algorithm** | Equihash |

**Example with nheqminer (CPU):**

```bash
nheqminer.exe -l 178.104.208.90:3093 -u YOUR_RWC_ADDRESS.worker1 -t 3
```

<details>
<summary><b>More miner examples</b> (click to expand)</summary>

<br>

**nheqminer on Linux**

```bash
./nheqminer -l 178.104.208.90:3093 -u YOUR_RWC_ADDRESS.worker1 -t 3
```

**miniZ on Windows**

```bash
miniZ.exe --url=YOUR_RWC_ADDRESS.worker1@178.104.208.90:3092 --pass=x --par=200,9 --pers=ZcashPoW
```

**miniZ on Linux**

```bash
./miniZ --url=YOUR_RWC_ADDRESS.worker1@178.104.208.90:3092 --pass=x --par=200,9 --pers=ZcashPoW
```

Replace `YOUR_RWC_ADDRESS` with the mining address you created in the wallet.

</details>

<img src="divider.svg" width="100%" alt="">

## Pool details

| Setting | Value |
|:---|:---|
| **Pool fee** | 1.5 % |
| **Payout scheme** | PPLNS |
| **Block reward** | 50 RWC |
| **Payout interval** | every 10 minutes |
| **Minimum payout** | 0.01 RWC |
| **Block maturity** | 100 confirmations |

> [!IMPORTANT]
> Rewards from a block become payable only after it has **100 confirmations**, so there is a delay between finding a block and receiving the payout.

<img src="divider.svg" width="100%" alt="">

## Join the network

We are looking for:

- GPU and CPU miners
- Node operators
- Infrastructure sponsors
- VPS partners
- Web3 developers

<img src="divider.svg" width="100%" alt="">

## Mission

Building a secure and decentralized blockchain ecosystem.

<br>

<div align="center">

[![Website](https://img.shields.io/badge/WEBSITE-rewecoin.com-e10600?style=for-the-badge&labelColor=0a0000)](https://rewecoin.com)
[![Pool](https://img.shields.io/badge/START_MINING-pool.rewecoin.com-ffd700?style=for-the-badge&labelColor=0a0000)](https://pool.rewecoin.com)

</div>

<img src="circuit-board.svg" width="100%" alt="">
