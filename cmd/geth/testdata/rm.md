./etica-geth --datadir=/home/panda/.etica init etica_genesis.json

./etica-geth --datadir /home/panda/.etica --port 30311 --http --http.port 9721 --http.api personal,eth,net,web3,admin,txpool,debug --cache=8000 --maxpeers 100 --syncmode full --password /home/panda/.elh/.elh-pw --nat any --allow-insecure-unlock --snapshot=false

./etica-geth --datadir /home/panda/.etica account new

0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A

./etica-geth --datadir /home/panda/.etica --port 30311 --http --http.port 9721 --http.api personal,eth,net,web3,admin,txpool,debug --cache=8000 --maxpeers 100 --syncmode full --password /home/panda/.elh/.elh-pw --nat any --allow-insecure-unlock --snapshot=false --mine --miner.etherbase 0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A --unlock 0xB36D6cC2C8935eCeBcF9F64e45A6Ba11d634858A

./etica-geth attach /home/panda/.aves/geth.ipc

admin.addPeer("enode://...")

admin.peers <<< to show peers list
