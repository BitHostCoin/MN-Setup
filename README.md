# MN-Setup Guide (Follow below Steps)

wget -q https://raw.githubusercontent.com/BitHostCoin/MN-Setup/master/bithostinstall.sh

sudo chmod +x bithostinstall.sh

./bithostinstall.sh

When prompted to Enter your bithost Masternode GEN Key.

Paster your Masternode GEN Key and press enter

Wait till Node is fully Synced with blockchain.
For check enter below command.

bithost-cli getinfo

When Node Fully Synced enter below command for check masternode status.

bithost-cli masternode status
