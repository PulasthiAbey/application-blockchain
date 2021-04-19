# application-blockchain
Please use linux base os or linux subsystem to run this network ##########
Hardware requrement- minimum(4GB RAM with 1.6GHz processer) Recomended(8GB RAM with core i3 or higher)########


1) install Hyperledger fabric 
2) Download the zip file from the github
3) exatract the blockchain_app-main.zip file
4) copy blockchain_app-main folder inde into the  "fabric-samples/fabcar/" folder
5) copy fabcar.js from fabric-samples/fabcar/blockchain_app-main/fabcar/fabcar.js
6) replace "fabcar.js" file with "fabric-samples/chaincode/fabcar/javascript/lib/fabcar.js"  
7) open the terminal and set route inside to the "fabric-samples/fabcar"
8) run neworkDown.sh (./neworkDown.sh)
9) run startFabric.sh with javascript (./startfabric.sh javascript)
10) change directry inside to the qpiserver folder 
11) install nodemodals (npm install)
12)delete all  inside the  "fabric-samples/fabcar/blockchain_app/wallet" if there any file
13)run enrollAdmin.js with node (node enrollAdmin.js)
14)run registerUser.js with node (node registerUser.js)
15)run apiserver.js with node (node apiserver.js)
16)run app.py inside the "/fabric-samples/fabcar/blockchain_app/views"
17)take the server link from python terminal and paste in the browser.
