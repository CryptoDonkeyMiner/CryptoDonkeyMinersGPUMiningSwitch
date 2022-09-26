# CryptoDonkeyMiners GPU Mining Switch
GPU Mining Switch, GPU Mining Profit Switch

See how it works here: https://youtu.be/-eIxYGKBltc

Feature requests and bug reporting in Discord here: https://discord.gg/6VNqReGzDa

CryptoDonkeyMiners GPU Mining Switch will help you mine the most profitable cryptocurrency by calling your pre-defined batch files and switching over to the most profitable cryptocurrency.

The following cryptocurrencies are supported:
* AETERNITY
* AION
* BEAM
* CONCEAL
* CONFLUX
* CORTEX
* ERGO
* ETHEREUMCLASSIC
* ETHEREUMPOW
* FIRO
* GEMLINK
* KASPA
* NEOXA
* RAVENCOIN
* RYO
* SERO
* SWAP
* ZANO
* NICEHASH-ETHASH
* NICEHASH-ETCHASH
* NICEHASH-KAWPOW
* NICEHASH-BEAMV3
* NICEHASH-CUCKOOCYCLE
* NICEHASH-CUCKATOO32
* NICEHASH-ZHASH
* NICEHASH-AUTOLYKOS
* NICEHASH-OCTOPUS
* NICEHASH-RANDOMX

You need to set the following global settings:
* kWh cost in USD - The cost will determine profits or loss
* Check delay in minutes - How many minutes should pass before the next crypto mining profitability check

You need to set the following coin settings for each coin you want to mine:
* Hashrate - The hashrate, as seen on www.whattomine.com
* Watts - How many watts your mining consumes
* Batch path and file - The file path, like c:\miner\lolminer\mine_ergo.bat
* Enabled - If box is checked, will include in profitability check
* Skip if negative profit - Checking this on a coin will skip mining it if there is a loss on it. It will stop (or never start) the miner if all coins have it checked and no coins are profitable. If left unchecked on one coin, it will fallback and mine that. If left unchecked on multiple, it will mine the most profitable, even at a loss.

Please use the save button to save your settings inbetween coin setups.

My YouTube Channel: https://www.youtube.com/cryptodonkeyminer

![image](https://user-images.githubusercontent.com/89296512/192139111-78c13f36-3265-4321-89c4-6c4deafeda46.png)

It will work with all miners that can be started from a batch (.bat) file, just to mention a few:
* Lolminer
* Trex miner
* GMiner
* NBMiner
* MiniZ Miner
* BzMiner
* Team Black Miner
* WildRig Multi Miner
* XMRig

I stopped testing after that, as it should work with everything.

If you are using a miner where you cannot set the GPU mining overclock settings in the specific batch file, I recommend that you use lolNvidiaOC. You can set your overclock settings in the batch file using that. Get it here:
https://github.com/Lolliedieb/lolMiner-releases/wiki/Guide-Windows-(LHR,Watchdog,WebServer,OC)

