# 🌐 Connect to Platform

Now that you have a wallet installed, let's connect it to Dynamo AI and get you ready to use AI services.

## Before You Connect

### Pre-Connection Checklist

- ✅ Wallet is installed and set up
- ✅ You have a small amount of ETH for transaction fees
- ✅ Wallet is unlocked and ready
- ✅ You're on the official Dynamo AI website

**First Connection**: The process takes about 2 minutes and only needs to be done once per device.

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
