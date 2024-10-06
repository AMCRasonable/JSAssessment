/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
const NFT_ana = []


// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (_nickname, _sticker, _accessory, _bling) {
   const NFT = {
      "nickname": _nickname,
      "sticker": _sticker,
      "accessory": _accessory,
      "bling": _bling
   }
   NFT_ana.push(NFT);
   console.log("Minted: " + _nickname);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
   for ( let i = 0; i < NFT_ana.length; i++){
      console.log("\nID: \t\t" + (i + 1));
      console.log("Nickname: \t" + NFT_ana[i].nickname);
      console.log("Sticker: \t" + NFT_ana[i].sticker);
      console.log("Accessory: \t" + NFT_ana[i].accessory);
      console.log("Bling: \t\t" + NFT_ana[i].bling);
   }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
   console.log("\n" + NFT_ana.length);
}

// call your functions below this line
mintNFT("Ana", "Panda", "Necklace", "Gold Chain");
mintNFT("Mary", "Strawberry", "Ring", "Gold Chain");
mintNFT("Colin", "Heart", "Bracelet", "Gold Chain");

listNFTs();
getTotalSupply();
