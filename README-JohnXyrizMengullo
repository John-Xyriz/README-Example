## MengulloToken

Simple overview of use/purpose.
Hello! This code is intended for the creation of a token on the Ethereum blokchain. It facilitates actions such as token creation, known as minting, and token destruction, referred to as buring. This particular token named is "MengulloToken" with an abbreviation "MTJ". It monitors both the total supply and the balances of each address. Thank you!.

## Description

An in-depth paragraph about your project and overview of use.
The MyToken contract, nameD "MengulloToken" (MTJ), provides essential token features on the Ethereum blockchain. It sets the token name, abbreviation, and total supply through public variables and utilizes mappings to track the balances of the users of it. Thank you!

## Getting Started

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders
## How/where to download your program

This program can be downloaded from this website (Remix IDE). It is Solidity Integrated Development Environment (IDE) that enables programmers or developers to create and deploy their own smart contracts on the Ethereum blockchain.

## Any modifications needed to be made to files/folders

In reality, there are no further modifications required to files or folder after downloading the program. All necessary components can be directly accessed within the Remix IDE. Download this program from the Remix IDE website, and you can start creating your code and deploying your own smart contracts here.

## Executing program

To execute this program, you need to understand and follow carefully the provided instructions.
  • Open your code editor and open the file containing the MyToken contract.

  • Ensure that you have the correct environment for deploying your smart contract on the blockchain network.

  • Within your contract, you will fidn the following steps:

      Step A: Set the name and abbreviation of your token by updating the tokenName and tokenAbbrv variables.

      Step B: Establish the intial supply of your token by updating the totalSupply variable.

      Step C: Add addresses and their balances using the mint function.

      Step D: Choose addresses and initiate the token reduction process using the burn function.

  • Follow the comments inside the code to understand each part of the contract.

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
contract MyToken {
     // public variables here
    string public tokenName = "MengulloToken";
    string public tokenAbbrv = "MTJ";
    uint256 public totalSupply;
    // mapping variable here
    mapping(address => uint256) public balances;
    // mint function
    function mint(address _to, uint256 _value) public {
        totalSupply += _value;
        balances[_to] += _value;
    }
    // burn function
    function burn(address _from, uint256 _value) public {
        require(balances[_from] >= _value, "Insufficient balance to burn");
        totalSupply -= _value;
        balances[_from] -= _value;
    }
}
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```
Here are some tips fo encountering common problems.

When encountering issues with accessing your token, ensure that your permissions are correct.

If there are errors in minting and burning tokens, check your functions for possible misuse or small details.

Ensure that your variables and data types are correct to avoid compilation and runtime errors in your smart contract.

Be cautious in evaluating your conditions and assertions to avoid potential security and safety issues.

When facing issues with the execution and operation of your smart contract, simply debug using tools such as Ganache to analyze or check your created code and identify potential problems


## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)
  [NTC-S] John Xyriz Estela Mengullo 
  422003755@ntc.edu.ph


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details
This project is licensed under the [MIT] License - see the LICENSE.md file for details
