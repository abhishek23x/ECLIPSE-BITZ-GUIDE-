# ECLIPSE-BITZ-GUIDE-

## COMMANDS👇🏻
```

sudo apt-get update && sudo apt-get upgrade -y

sudo apt install screen curl nano  -y

```

```bash 
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```bash
source $HOME/.cargo/env
```

```bash 
curl --proto '=https' --tlsv1.2 -sSfL https://solana-install.solana.workers.dev | bash
```
```bash
solana config set --url https://mainnetbeta-rpc.eclipse.xyz/
```

* Now Create a Wallet
```bash
solana-keygen new
```
* Set Passphrase for better security or just skip (click enter)
* Save Public Key

* NOW Export Private Key :


```bash
solana config get
```
```
 cat ~/.config/solana/id.json
```

* NOW Install Bitz CLI
```bash
cargo install bitz
```

```bash
screen -S eclipse
```

```bash
bitz collect
```
Send 0.005 $ETH on Eclipse to start mining.

Other Commands:

  •	Claim your Bitz:
```bitz claim```
  
  •	Check your balance:
```bitz account```

  • Config CPU (change the number to change cores):
```bitz collect --cores 8```
  
  •	View all commands:
```bitz -h```

