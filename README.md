# Getting Started with the product

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

##Pre-requisite
NodeJs

## To run the program, follow these steps

In the project directory, once you clone the repo:

### `npm install`
This installs all the dependency of the package.json file

### `npm run`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

- In the first step, make sure you have generated key-pairs from Veramo. Insert the generated key in the field.
- Mention people you want to give priority to in the family option. These people will receive the shares of double weight
- In the friends option, mention people you are want to share your key. These will receive one share each.
- Now enter the minimum number of shares(threshold) you want to receive to recover your key.
Note: Please make sure that the threshold signifies the number of shares, not the number of people.
- Enter Submit 

 Your private key will be partitioned into shares and distributed among your friends and family where family will receive key with two shares and friends will receive key with one share. For eg: If you assign mom in family, she will receive a key with two shares and your friend Bob will receive a key with 1 share. 
 
### In the recovery process
 - Select family and friends in a way to reach the threshold number of shares mentioned during the partition of key.
 - Enter Submit\
  The key will be recovered successfully and shown in the screen.
 
 

