# IPFS Upload - Using Infura API

- This is a simple React App using which you can upload any file to IPFS and it will generate an IPFS hash and a link which can be then shared with people or used however you want.
- Since, Infura discontinued its free IPFS service you will need an API key to use it.

### Note

For WindowsOS use some linux based terminal emulator like [WSL](https://learn.microsoft.com/en-us/windows/wsl/) or [GitBash](https://gitforwindows.org/)

## 🎬 Demo Video

https://user-images.githubusercontent.com/71545386/197403658-6c77614c-cb20-435b-87ec-9dcf0c918a18.mov

## 🔧 Setting up Local Development

Required:

- [Node v17](https://nodejs.org/download/release/latest-v17.x/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install/)
- [Git](https://git-scm.com/downloads)

1. Clone the repo and install `node_modules`

```bash
git clone https://github.com/codeTIT4N/IPFS-upload.git
cd IPFS-upload
yarn
```

2. Rename the `.env.example` file to `.env` and set the secret variables accordingly.

> You can get these by signing up for the infura IPFS service. It requires a credit card but they won't charge you until you cross the free 5GB limit.

3. Run the application:

```bash
yarn start
```

The site is now running at `http://localhost:3000`!
Open the source code and start editing!
