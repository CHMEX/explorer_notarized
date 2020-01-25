
With this Patch you can show the last Notarized height on a Insight Explorer.

Clone the Repo and chmod +x patch.sh

After that execute it with ./patch.sh  ASSETCHAIN

It copies four new files working example is here https://kmd.explorer.dexstats.info/

NOTE: This will remove also the Scan Option ( https://github.com/CHMEX/explorer_notarized/blob/master/header.html#L43 ) on the Insight Explorer make modifications to your needs in header.html

Changed Parts are:  
- https://github.com/CHMEX/explorer_notarized/blob/master/bitcoind.js#L2098
- https://github.com/CHMEX/explorer_notarized/blob/master/status.html#L96
- https://github.com/CHMEX/explorer_notarized/blob/master/status.js#L63
- https://github.com/CHMEX/explorer_notarized/blob/master/header.html#L39

25.01.2020
Update: add KMDversion

