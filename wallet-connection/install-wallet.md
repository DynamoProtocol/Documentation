# 📱 Install a Wallet

We'll walk you through setting up MetaMask, the most popular and user-friendly wallet for accessing Dynamo AI.

## Why MetaMask?

- 🔒 **Secure** - Industry-leading security standards
- 🎯 **User-Friendly** - Simple interface for beginners
- 🌐 **Universal** - Works with thousands of applications
- 📱 **Multi-Platform** - Browser extension and mobile app

---

## Installing MetaMask

### Step 1: Download MetaMask

1. **Visit**: [metamask.io](https://metamask.io)
2. **Click "Download"**: Choose your browser
3. **Add Extension**: Click "Add to Chrome" (or your browser)
4. **Confirm Installation**: Click "Add Extension" in the popup

**Security Check**: Always download MetaMask from the official website. Never install from unofficial sources.


### Step 2: Set Up Your Wallet

After installation, MetaMask will open automatically:

1. **Click "Get Started"**
2. **Choose "Create a Wallet"** (for new users)
3. **Create Password**: Choose a strong, unique password
4. **Backup Your Seed Phrase**: This is the most important step!

### Step 3: Secure Your Seed Phrase

{% hint style="danger" %}
**Critical Step**: Your seed phrase is the master key to your wallet. If you lose it, you lose access to your funds forever.
{% endhint %}

**MetaMask will show you 12 words**:

1. **Write them down** on paper in the exact order
2. **Store safely** - consider a fireproof safe
3. **Never store digitally** - no photos, emails, or cloud storage
4. **Verify** by entering the words back in the correct order

#### Seed Phrase Security Tips

- ✅ **Multiple copies** - Store in 2-3 separate secure locations
- ✅ **Metal backup** - Consider stamping words into metal for fire protection
- ✅ **Tell trusted person** - Where to find it if something happens to you
- ❌ **Never digital** - No screenshots, no cloud storage
- ❌ **Never share** - MetaMask will never ask for your seed phrase

### Step 4: Complete Setup

1. **Confirm Seed Phrase**: Enter the words in the correct order
2. **Agree to Terms**: Read and accept MetaMask's terms of service
3. **Pin Extension**: Click the puzzle piece icon in your browser and pin MetaMask
4. **Success!**: You now have a MetaMask wallet ready to use

---

## Alternative Wallet Options

### For Mobile Users

#### Trust Wallet

1. **Download**: From App Store or Google Play
2. **Create Wallet**: Follow the setup wizard
3. **Secure Seed Phrase**: Write down your recovery words
4. **Enable WalletConnect**: For connecting to Dynamo AI

#### Rainbow Wallet

1. **Download**: Available for iOS and Android
2. **Beautiful Interface**: Designed for ease of use
3. **Built-in DeFi**: Easy token swapping
4. **WalletConnect Ready**: Seamless connection to web apps

### For Advanced Users

#### Hardware Wallets

- **Ledger Nano S/X**: Ultimate security for large amounts
- **Trezor**: Another secure hardware option
- **Connect via MetaMask**: Use hardware wallet with MetaMask interface

---

## After Installation

### Fund Your Wallet

You'll need ETH for transaction fees:

1. **Buy ETH** on an exchange (Coinbase, Binance, etc.)
2. **Send to wallet** using your wallet address
3. **Start small** - $50-100 ETH is plenty to begin

### Get Your Wallet Address

1. **Open MetaMask**
2. **Click account name** at the top
3. **Copy address** - this is your public address for receiving funds

{% hint style="info" %}
**Your Address**: Think of this like your email address - it's safe to share publicly for receiving payments.
{% endhint %}

---

## Security Best Practices

### Password Security

- **Unique password** - Don't reuse from other accounts
- **Strong password** - Mix of letters, numbers, symbols
- **Password manager** - Consider using one to generate and store

### Browser Security

- **Keep updated** - Always use the latest browser version
- **Secure browsing** - Only visit trusted websites
- **Clear cache** - Regularly clear browser data

### General Safety

- **Bookmark** the official Dynamo AI site
- **Double-check URLs** - Watch for phishing attempts
- **Start small** - Test with small amounts first
- **Stay informed** - Follow official channels for security updates

---

## Troubleshooting Installation

### Common Issues

**Extension won't install:**

- Try a different browser
- Disable other extensions temporarily
- Clear browser cache and try again

**Can't see MetaMask icon:**

- Check browser's extension management
- Pin the extension to your toolbar
- Restart browser after installation

**Forgot password:**

- Use "Import wallet" with your seed phrase
- Set a new password
- Never lose your seed phrase!

---

**Next Step**: [Connect to Platform](connect-platform.md) to link your wallet with Dynamo AI.

---

## wallet-connection/connect-platform.md

---

description: Connect your wallet to Dynamo AI and start using AI services
---

# 🌐 Connect to Platform

Now that you have a wallet installed, let's connect it to Dynamo AI and get you ready to use AI services.

## Before You Connect

### Pre-Connection Checklist

- ✅ Wallet is installed and set up
- ✅ You have a small amount of ETH for transaction fees
- ✅ Wallet is unlocked and ready
- ✅ You're on the official Dynamo AI website

{% hint style="info" %}
**First Connection**: The process takes about 2 minutes and only needs to be done once per device.
{% endhint %}

---

## Step-by-Step Connection

### Step 1: Visit Dynamo AI

1. **Go to**: [ai.dynamo.zone](https://ai.dynamo.zone)
2. **Verify URL**: Ensure you're on the official site
3. **Check security**: Look for the lock icon in your browser

### Step 2: Initiate Connection

1. **Locate "Connect Wallet"**: Top-right corner of the page
2. **Click the button**: This opens the wallet selection modal
3. **Choose your wallet**: Select MetaMask or your preferred option

### Step 3: Approve Connection

When you click connect, MetaMask will popup:

1. **Review permissions**: See what Dynamo AI is requesting
2. **Select account**: Choose which wallet account to connect
3. **Click "Connect"**: Approve the connection request

{% hint style="warning" %}
**Permission Review**: Dynamo AI only requests permission to see your wallet address and request transactions. We never request access to move funds automatically.
{% endhint %}

### Step 4: Sign Authentication Message

After connecting, you'll be prompted to sign a message:

1. **Message appears**: "Authenticate to Dynamo AI: [timestamp]"
2. **Click "Sign"**: This proves you own the wallet
3. **No cost**: Signing messages is free - no gas fees

#### Why Sign a Message?

- **Security**: Proves you control the wallet
- **Authentication**: Creates a secure session
- **No risk**: Signing doesn't give access to your funds
- **Standard practice**: Used by all reputable Web3 applications

---

## Connection Confirmation

### Success Indicators

You'll know the connection worked when you see:

- ✅ **Wallet address** displayed in the top-right corner
- ✅ **Network indicator** showing current blockchain
- ✅ **Balance display** in the sidebar (may show 0 initially)
- ✅ **Green status** indicators

### Your Connected Wallet Info

The interface will show:

- **Shortened address**: Like "0x1234...5678"
- **Current network**: Should show "ARBITRUM"
- **Connection status**: Green indicator for active connection

---

## Network Configuration

### Automatic Network Switching

Dynamo AI works on **Arbitrum** network for lower fees:

1. **Switch prompt**: You'll see "Switch to Arbitrum" notification
2. **Click "Switch Network"**: Approve the network change
3. **Add network**: If Arbitrum isn't in your wallet, approve adding it
4. **Confirmation**: Wait for the switch to complete

### Arbitrum Network Details

If you need to add manually:

- **Network Name**: Arbitrum One
- **RPC URL**: <https://arb1.arbitrum.io/rpc>
- **Chain ID**: 42161
- **Currency Symbol**: ETH
- **Block Explorer**: <https://arbiscan.io>

{% hint style="success" %}
**Why Arbitrum?** Same security as Ethereum but with ~90% lower transaction fees and faster confirmation times.
{% endhint %}

---

## Managing Your Connection

### Disconnect Wallet

To disconnect your wallet:

1. **Click wallet address** in top-right corner
2. **Select "Disconnect"**: Ends the session
3. **Confirm**: Your wallet is now disconnected

### Reconnecting

To reconnect later:

1. **Click "Connect Wallet"** again
2. **Wallet auto-connects**: If you used the same browser
3. **Sign new message**: Create a fresh authentication session

### Multiple Accounts

If you have multiple wallet accounts:

1. **Switch in MetaMask**: Change the active account
2. **Refresh page**: Dynamo AI will detect the new account
3. **Sign new message**: Each account needs separate authentication

---

## Troubleshooting Connection Issues

### Connection Failed

**Wallet popup doesn't appear:**

- Ensure MetaMask is unlocked
- Try refreshing the page
- Check if popup was blocked by browser

**"Transaction rejected" error:**

- You clicked "Reject" instead of "Connect"
- Try connecting again
- Make sure you're approving, not rejecting

### Network Issues

**Wrong network error:**

- Click "Switch Network" when prompted
- Manually switch to Arbitrum in MetaMask
- Refresh page after switching

**Network not found:**

- Approve adding Arbitrum when prompted
- Add network details manually if needed
- Contact support if problems persist

### Authentication Problems

**Signature request fails:**

- Make sure wallet is unlocked
- Don't reject the signature request
- Try disconnecting and reconnecting

**"Authentication expired":**

- Your session timed out (normal after 8 hours)
- Simply reconnect to create a new session
- No need to do anything special

---

## Security During Connection

### What to Verify

- ✅ **Official URL**: Only connect on ai.dynamo.zone
- ✅ **HTTPS connection**: Look for lock icon in browser
- ✅ **Reasonable permissions**: We only request basic access
- ✅ **No unexpected prompts**: We won't ask for seed phrases

### Red Flags - Never Do This

- ❌ **Enter seed phrase**: Dynamo AI never asks for this
- ❌ **Send ETH first**: No upfront payments required
- ❌ **Download software**: Everything works in your browser
- ❌ **Share private keys**: Keep these secret always

**Phishing Protection**: Always double-check the URL. Scammers create fake sites with similar addresses.


---

**Next Step**: [Network Setup](network-setup.md) to optimize your connection for the best experience.

---
