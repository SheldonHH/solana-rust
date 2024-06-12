Save this seed phrase and your BIP39 passphrase to recover your new keypair:
market rally tone flip nose penalty exchange believe audit antique double blur
```bash
solana-keygen new -o /home/joec/.config/solana/id.json
```
    
   
```bash
solana config set --keypair /home/joec/.config/solana/id.json
```
   
Establish Connection to netwk
```bash
solana config set --url https://api.devnet.solana.com
```

hello-solana
```bash
cd Rust-Solana/hello-solana
npm cache clean
npm install
npm run build:program
```