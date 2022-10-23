# IPFS Upload - Using Infura API

- This is a simple React App using which you can upload any file to IPFS and it will generate an IPFS hash and a link which can be then shared with people or used however you want.
- Since, Infura discontinued its free IPFS service you will need an API key to use it.
## 🎬 Demo Video 


https://user-images.githubusercontent.com/71545386/197403658-6c77614c-cb20-435b-87ec-9dcf0c918a18.mov


##  🔧 Setting up Local Development

Required: 
- [Node v17](https://nodejs.org/download/release/latest-v17.x/)  
- [Yarn](https://classic.yarnpkg.com/en/docs/install/) 
- [Git](https://git-scm.com/downloads)

Clone the repo and install the node_modules
```bash
git clone https://github.com/codeTIT4N/IPFS-upload.git
cd IPFS-upload
yarn
```
Rename the .env.example to .env and set the following secret variables accordingly:
1. REACT_APP_INFURA_PROJECT_ID
2. REACT_APP_INFURA_PROJECT_SECRET

You can get these by signing up for the infura IPFS service. It requires a credit card but they won't charge you until you cross the free 5GB limit.

To run the application:
```bash
yarn start
```
The site is now running at `http://localhost:3000`!
Open the source code and start editing!
