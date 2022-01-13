Preparation
Open Terminal
create a new folder
npx create-next-app nft-mktplace
click enter
click yes then enter
change directory to nft-mktplace
view all installed packages,make sure its fine.
Now install dependencies using npm install or yarn add
install 
yarn add ethers hardhat @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers web3modal @openzepplin/contracts ipfs-http-client axios 
click enter
lastly, install
yarn add -D tailwindcss@latest postcss@latest autoprefixer@latest
click enter
 next  initialize some configuration for tailwind using npx
npx tailwindcss init -p
click enter

NOTE
if you are using Mac or window terminal use 
code .
to open VS code
if you are downloding all this time on vs code you dont do anything 
Go to stlyes drop down menu and select globals.css
Overide all code inside and replace with yours (Optional)
Replace with
@tailwind base;
@tailwind components;
@tailwind utilities;


Writing Solidity Code:
first run 
npx hardhat
click enter
select create a sample project
click enter
click enter y 

add accounts details to hardhat.js

replace with
NFT.sol
and
NFTMarket.sol

TESTING
Open test folder
sample-test.js 
 delete greeter.sol
start writing functions for the tests.

then go to 
Terminal 
npx hardhat test
click enter

Test  should  return:

 BigNumber { value: "2" },
    '0xe7f1725E7734CE288F8367e1Bb143E90bb3F0512',
    BigNumber { value: "2" },
    '0xf39Fd6e51aad88F6F4ce6aB8827279cffFb92266',
    '0x0000000000000000000000000000000000000000',

Create and run additional test for sales

