# DApp : Food Delibery with Block-Chain
Food Delibery DApp(Decentralized Application) using Ethereum Protocol <br>
/ Implementation of Block Chain Algorithm on Browser using Angular, React, Vue, Node.js with Typescript

## Environment

- OS : Linux Ubuntu 18.04
- Web Server for web client interface : Node.js v12.16.0
- Package Manager : npm 6.13
- IDE : truffle 5.1.X
- Smart Contract Language Toolchain : Solidity 0.8.1
- Browser/Web Client : Chrome, MetaMask Plugin(LTS)
- Editor : Atom
- UML : diagrams.net

## ETC

### Transpiling TypeScript

(If you are using Node.js Runtime)
```cmd
# (node, npm version check)
# node -v
# npm -v

(install typescript transpiler globally)
npm install -g typescript

# (typescript version check)
# tsc -v

(transpiling typescript to javascript with no overwriting until there are no errors)
tsc (tsc_file_name) --noEmitOnError true

# (or you can use '--t' flag for specific javascript version) 
# tsc --t ES5 (tsc_file_name)

> Then js file is generated!
```
