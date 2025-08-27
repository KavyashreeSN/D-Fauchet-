# 💰 Token Project (Motoko on Internet Computer)

This is a simple **token project** built using the Internet Computer (IC) and the **Motoko** programming language.  
It demonstrates how to create, deploy, and interact with a basic token canister on the IC.

---

## 🚀 Features
- Create your own token on the Internet Computer
- Mint, transfer, and check balances
- Simple frontend connected to the deployed canisters

---

## 🛠️ Getting Started

###  Clone this repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>


Install DFX (Internet Computer SDK):

Follow the official guide:
👉 https://internetcomputer.org/docs/current/developer-docs/getting-started/install/


Verify installation:

dfx --version

Start the local replica
dfx start --background

Deploy the canisters
dfx deploy

After deployment, you will get your canister IDs for:
token , token_assets

Check them with:

dfx canister id token
dfx canister id token_assets

Update the frontend :

Replace the default canister IDs inside the frontend code with your own.
This ensures the UI connects to your deployed token.

After deploying, open your frontend locally:

dfx deploy

📖 Notes :

The frontend may appear blank until you connect it to your own canister IDs.

This project is for learning purposes — not a production-ready token.
