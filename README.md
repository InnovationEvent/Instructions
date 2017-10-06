# Event Instructions
Read on if you have registered for participation in one of our Hands-On Blockchain event. It is very important that you come prepared for the workshop. 

# What does it mean to be prepared?
* You MUST get your own machine (PC/Mac/Linux - all good)
* Minimum Recommended: 8GB RAM, 50GB Disk space, Decent CPU
* You MUST have administrative rights on the machine
* You MUST be able to connect to public wi-fi 
* You MUST install/setup various software that will be needed for workshop
* You MUST be comfortable with coding
* If you are joining us JUST for the afternoon session - Please refer to the note on reading list at the end of this document.

If you do not meet the above requirements, we suggest that you un-register and plan for a future event as you would not benefit from the workshop.

**PS**
Our team will not be able to provide support for Tools installation & setup issues during the event. If you face any issue then this is the time to get it resolved. Use the issues link, if you face any problem .... https://github.com/TcsInnovationEvent/Instructions/issues

# What if I face issues?

There is tons of information available on ineternet to solve most of the common problems. We suggest that before asking the organizers to help you with an issue, search the web and try to address the issue on your own. If you are able to solve the issue share it with other by opening an issue + solution ... this would help others.

To raise and track issues we use GitHub Issues. Simply click on issues and add .... folks are looking at these issues and will do their best to help you out. If the issue you are facing cannot be solved due to challenges on your machine, you may have to arrange an alternative.

[Open new issue](https://github.com/TcsInnovationEvent/Instructions/issues)



![Link to issues](https://user-images.githubusercontent.com/32396416/31078861-c79319c2-a751-11e7-921b-dd79c3669e4d.png)



Make sure to provide all relevant information for the issue you are facing, include:
* What are you trying to do?
* What OS/Machine + Version e.g., Windows 10?
* Clearly explain what is the issue
* Provide a screenshot of the issue
* Have you looked up on Google? What did you do try resolving the issue on your own?

We suggest that you work on setting up your machines as soon as possible to have enough time to get all issues (if any) addressed.

# InsurTech/Hartford  Oct 11, 2017

1. Ensure you have Google Chrome installed on your machine

2. Install MetaMask Chrome plugin using the instructions below

    https://metamask.io
    
3. MetaMask Setup : Follow the instruction in the document:  *Install MetaMask and Get Ethers.pdf*
    
3. Install Node v6.x  [PLEASE DO NOT Install v7x or v8x]

    https://nodejs.org/en/download/
    
    After the installation, please verify the versions:
    > node -v        v6.x
    > npm  -v        v5.x

4. Install Visual Code (Community)

   https://www.visualstudio.com/vs/community/
   
   > Add the extension for Solidity to VCode
   
5. Clone the repository

   https://github.com/InnovationEvent/HelloEthereum
   
   > Open it in Visual Code - solidity code should be color coded

6. Install Truffle

   > npm install -g truffle
   
   Read documentation here:
   
   http://truffleframework.com/docs/
   
   ****Validate****
   In a terminal window
   > truffle version
   Create a directory and cd to it, run this command:
   > truffle init
   
   Last command generates the Truffle project .... on Windows (only) you need to rename the truffle.json to truffle-config.json
   
7. Install TestRPC

   > npm install -g ethereumjs-testrpc
   
   Read the documentation here:
   
   https://github.com/ethereumjs/testrpc
   
   ****Validate****
   In a terminal window
   > testrpc             It should show a bunch of log messages & no error

8. Bookmark these links in your Google Chrome

    * https://github.com/InnovationEvent
    * https://wallet.ethereum.org/
    * https://remix.ethereum.org
    * https://faucet.rinkeby.io/
    * http://faucet.ropsten.be:3001
  

9. Install Ethereum Wallet (Optional)
   
   https://ethereum.org
   
   * Connect to ROPSTEN or TestNet
   * This would download complete chaindata which may take a few hours to day or 2
   * You will be able to mine for Test ethers - go ahead do it if you can !!!

10. Git client + Understanding of basic git commands
  
    https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf
    

Weekend Reading List:
=====================
If you are coming JUST for the afternoon session only then we are assuming that you have an idea on the fundamentals of Blockchain and Ethereum......either way we suggest that you go through the material available here: http://ethereum101.org/

* Ethereum terminology - Ethers, Gas, Consensus ... Google and you will find tons of information  
* General Blockchain Technology articles
* Ethereum & Smart contracts
* Solidity fundamentals
* Testing frameworks specifically Mocha and Chai
