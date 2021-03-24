# IOTAN Wallet and Mining
IOTAN Mining 1.0

Mine IOTAN Coin for free. Easy to use. Tool for website mining coming soon.

First install and run the IOTAN GUI Wallet on Windows or Linux. Link to software here:

http://evolterr.com/6N3z

Use the following instructions to mine a block.

Open your wallet, and make sure your wallet is connected with a node. Your wallet is connected when you see the icon Wallet connections Scrypt and SHA256 in the lower right corner of your wallet.

The message “Syncing Headers (0,0%)” will disappear once you mine your first block.

Close your wallet and create the file iotan.conf in the folder “%APPDATA%\iotan\”.

Paste the following text into iotan.conf and save the file.

rpcuser=rpc_iotan rpcpassword=99f54b45238947d51aac1ba1c rpcallowip=127.0.0.1 rpcport=31577 listen=1 server=1

Open your wallet.

Create a .bat file named mine.bat in the same folder where you extracted iotan-cli.exe and paste the following text into mine.bat.

@echo off set SCRIPT_PATH=%cd% cd %SCRIPT_PATH% echo Press [CTRL+C] to stop mining. :begin iotan-cli.exe generate 1 goto begin

Save the file. 

Execute mine.bat to start mining your first block.

It will take about +/- 30 minutes to mine your first block, depending on your computer hardware.

#mining #free #coin#iotan#cpu#gui
