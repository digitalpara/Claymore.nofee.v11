# claymore dualminer v11 without developers fee

This is v11 of Claymore Ethereum Miner with the DevFee removed

You don't have to do anything, just start mining with the usual .bat

Check the .txt logs and look for "eth_submitLogin". If there are any where a different adress than yours appeard restart. Otherwise contact me.

This is undetected by the claymore software.

Executable is patched so you don't have to do anything, just start mining.

Once devfee mining is triggered it will mine to your address instead of developers. To make sure everything is working properly check the mining .txt logs for any "eth_submitLogin" where your address doesn't appear. If there are any then restart mining again and it should work properly. Otherwise contact me.

** FAQ **

How will I know this is working? In your pool You will see a new worker named "claymore_nofee" that will show up every few hours once Claymore DevFee activates

Does this work for future releases of Claymore ? No, I will manually update future Claymore releases.

I'm getting lower hashrate with your Claymore than original. Run it for at least 24 hours so that pool statistics even out from downtime where You swapped to Claymore 11.0 No Fee

Latest version is v11.0:
