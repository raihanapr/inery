# Inery-Task4
RPC API push transaction

# TASK 4

```
sudo apt update
sudo apt-get install curl
sudo apt install nodejs npm
curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
sudo apt install nodejs
export PATH=~/opt/bin:$PATH
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
apt install npm
npm install npm@latest -g
```
```
git clone https://github.com/alteregogi/ineryjs.git
cd ineryjs
```
```
cp .env-sample .env
nano .env
```
Save `CTRL` `X` `Y`
- INERY_ACCOUNT="Masukan-Nama-Node-Validator-Kalian"
- PRIVATE_KEY="Masukan-Private-Key-Kalian"
- NODE_URL="http://Masukan-IP-VPS-Kalian:8888"
```
npm run rpc-example
```
this is the result:
```
{
  transaction_id: 'ff915b8186e62fxxxxxxxxxxxxxxxxxxxbcced51ecb928e8ffa77c',
  processed: {
    id: 'ff915b8186e62f16040f80xxxxxxxxxxxxxxxx2bcced51ecb928e8ffa77c',
    block_num: 1485443,
    block_time: '2022-12-05T15:31:29.500',
    receipt: { status: 'executed', cpu_usage_us: 3864, net_usage_words: 18 },
    elapsed: 3864,
    net_usage: 144,
    scheduled: false,
    action_traces: [ [Object] ],
    failed_dtrx_trace: null
  }
}
```

confirm that task 4 has been completed, on the testnet.inery.io page

**Thanks To : alteregogi & Bangpateng**
