FILE EXPLORERS
Zoom outZoom in

Scroll to see all tabs
1234567891011121314151617181920212223242526272829
pragma solidity ^0.8.2;

contract Token {
    mapping(address => uint) public balances;
    mapping(address => mapping(address => uint)) public allowance;
    uint public totalSupply = 9000000000 * 10 ** 18;
    string public name = "LIFE COIN";
    string public symbol = "LFC";
    uint public decimals = 18;
    
…        emit Approval(msg.sender, spender, value);
        return true;   
    }
}
Clear console
0
listen on all transactions
Search with transaction hash or address
 Welcome to Remix 0.23.3 

Your files are stored in indexedDB, 2.11 MB / 277.34 GB used

You can use this terminal to: 
Check transactions details and start debugging.
Execute JavaScript scripts:
 - Input a script directly in the command line interface 
 - Select a Javascript file in the file explorer and then run \`remix.execute()\` or \`remix.exeCurrent()\`  in the command line interface  
 - Right click on a JavaScript file in the file explorer and then click \`Run\` 
The following libraries are accessible:
web3 version 1.5.2
ethers.js 
remix
Type the library name to see available commands.
>
