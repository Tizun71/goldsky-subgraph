**Install Dependencies**
```
npm install
```

**Getting Set up on Goldsky**

Create an account at [app.goldsky.com](https://app.goldsky.com/?ref=berachain.ghost.io)  
Create an API key on the [Settings page](https://app.goldsky.com/dashboard/settings?ref=berachain.ghost.io)  
Install the Goldsky CLI:  
```curl https://goldsky.com | sh```

**Build and deploy Subgraph on Goldsky**
```
npm codegen
npm build
goldsky login
goldsky subgraph deploy erc20-subgraph/1.0.0 --path .
```
