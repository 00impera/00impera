<div align="center">

# REWECOIN

![MAINNET](https://img.shields.io/badge/MAINNET-LIVE-red?style=for-the-badge&labelColor=black)
![MINING](https://img.shields.io/badge/MINING_POOL-ACTIVE-red?style=for-the-badge&labelColor=black)
![EXPLORER](https://img.shields.io/badge/EXPLORER-ONLINE-red?style=for-the-badge&labelColor=black)
![ALGO](https://img.shields.io/badge/ALGORITHM-EQUIHASH-red?style=for-the-badge&labelColor=black)

An independent Equihash blockchain with its own wallet, explorer and mining pool.

**Early-stage network:** hashrate is currently very low (around 1 Sol/s), so new miners have a real impact.

</div>

---

## Official links

| | |
|---|---|
| Website | https://rewecoin.com |
| Wallet | https://wallet.rewecoin.com |
| Explorer | https://explorer.rewecoin.com |
| Mining pool | https://pool.rewecoin.com |

---

## Network status

| Component | Status |
|---|---|
| Mainnet | Live |
| Mining pool | Active |
| Explorer | Online |
| Wallet | Online |
| Seed nodes | Coming soon |
| Worm Shield | Coming soon |

---

## Create your wallet and mining address

1. Open https://wallet.rewecoin.com and create (or open) your wallet.
2. Back up your recovery phrase offline. Anyone who has it can take your coins, and if you lose it you lose access.
3. Go to https://wallet.rewecoin.com/mining.html and click **Create mining address**.
4. Copy the new address from the "Mining addresses" table. Use it as your username in the miner.
5. Track found blocks, pending rewards and confirmed rewards on the same Mining page.

---

<div align="center">

## HOW TO MINE

![Server](https://img.shields.io/badge/SERVER-178.104.208.90-red?style=for-the-badge&labelColor=black)
![varDiff](https://img.shields.io/badge/PORT_3092-AUTO_DIFFICULTY-red?style=for-the-badge&labelColor=black)
![Fixed](https://img.shields.io/badge/PORT_3093-FIXED_DIFFICULTY-red?style=for-the-badge&labelColor=black)

</div>

- **Username:** your ReweCoin wallet address (optionally add a worker name: `ADDRESS.worker1`)
- **Password:** `x`
- **Algorithm:** Equihash

Example with nheqminer (CPU):

```
nheqminer.exe -l 178.104.208.90:3093 -u YOUR_RWC_ADDRESS.worker1 -t 3
```

---

## Pool details

| | |
|---|---|
| Payout scheme | PPLNS |
| Pool fee | 1.5 % |
| Block reward | 50 RWC |
| Payout interval | every 10 minutes |
| Minimum payout | 0.01 RWC |
| Block maturity | 100 confirmations |

Rewards from a block become payable only after it has **100 confirmations**, so there is a delay between finding a block and receiving the payout.

---

## Join the network

We are looking for GPU and CPU miners, node operators, infrastructure sponsors, VPS partners and Web3 developers.

---

## Mission

Building a secure and decentralized blockchain ecosystem.
