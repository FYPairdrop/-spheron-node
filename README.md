
# SPHERON WORKER NODE INCENTIVE

## Spek VPS

|  Hardware/VPS |  Minimum |
| ------------ | ------------ |
| CPU  | 4 or more physical CPU cores  |
| RAM | At least 8GB of memory (RAM) |
| Penyimpanan  | At least 100GB of SSD disk storage |
| Internet | At least 10mbps network bandwidth |

## Claim Faucet Arb Sepolia & Bridge to Spheron
- [Faucet 1](https://faucet.quicknode.com/arbitrum/sepolia) | [Faucet 2](https://www.alchemy.com/faucets/arbitrum-sepolia) | [Faucet 3](https://faucets.chain.link/arbitrum-sepolia) | [Faucet 4](https://learnweb3.io/faucets/arbitrum_sepolia/)
- Bridge Arb Sepolia to Spheron : [Here](https://spheron-devnet-eth.bridge.caldera.xyz/)

## Register Node
Sign up or log in through Gmail or Github
2. Click on the “Register New Fizz Node” Button and Connect your wallet

3. Select your node OS (linux), resources, Region, Payment Tokens, and Provider (sesuai vps kalian)

4. Setelah itu, Download file fizzup.sh

5. Transfers file script fizzup.sh to the root folder on VPS


## Run Node
  
### Update Packages:
```
sudo apt update && sudo apt upgrade -y install packages
```

### Install Docker:
```
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add - && sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable" && sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin -y
```

### Install file fizzup.sh:
```
chmod +x /root/fizzup.sh
```

### Run:
```
./fizzup.sh
```
<br>

### &#8212; Check Node Status: https://fizz.spheron.network/
<br>


### &#8212; If your node **Active** mint NFT Fizz Node

### &#8212; Join discord: https://discord.gg/9v5YQR3b
<br>

### &#8212; Claim role Fizzer: https://guild.xyz/spheronfdn
<br>

### :white_check_mark: Done!
<br>

### &#8212; Check Node Healty
```
docker compose -f ~/.spheron/fizz/docker-compose.yml logs -f
```
<br>
# -spheron-node
