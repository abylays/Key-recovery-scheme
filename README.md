# Social key recovery schemed for identity wallets


##Pre-requisite
NodeJs

## To run the program, follow these steps

In the project directory, once you clone the repo:

### `npm install`
This installs all the dependency of the package.json file

### `npm run`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Key generation and sharing process:
- First, ensure you have generated key-pairs using Veramo. 
- Specify individuals you wish to prioritize in the 'family' option. These individuals will receive shares with double weight.
- In the 'friends' option, list the people with whom you want to share your key. Each will receive a single share.
- Next, input the minimum number of shares (threshold) required to recover your key.
- Note: Ensure that the threshold represents the number of shares, not the number of individuals.
- Click 'Submit'.
- Your private key will be divided into shares and distributed among your friends and family. Family members will receive two shares each, while friends will get one share each. For example, if you list 'mom' under family, she will receive two shares, whereas your friend Bob will receive one share.

### Key recovery process:
- Choose family and friends in a manner that meets or exceeds the threshold number of shares specified during the key partition.
- Click 'Submit'.
- The key will be successfully reconstructed and displayed on the screen.
 
 

