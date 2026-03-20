# opencode-anthropic-oauth

**Fix "invalid token" in OpenCode — working OAuth solution for Anthropic Claude (Pro/Max)**

If your OpenCode setup stopped working with **Anthropic / Claude** and you're getting errors like:

> invalid token  
> authentication failed  
> unauthorized request  

👉 This plugin is a **working solution to restore access** and make everything run again.

---

## 🚀 What is this?

An open-source OpenCode plugin that allows you to:

- Authenticate with Claude Pro / Max
- Use Anthropic models inside OpenCode
- Bypass broken token flows
- Avoid installing Claude Code

💡 In short:  
**Fix OpenCode + Anthropic integration and make it work again.**

---

## 🔥 Why this exists

Recently, many users faced:

- invalid token opencode  
- Claude not responding  
- subscription not working in OpenCode  

This happens because Anthropic restricted how tokens are used.

👉 This plugin provides a **working OAuth-based method** to reconnect your account.

---

## ⚡ Installation

```bash
npm install -g opencode-anthropic-oauth
```

Add to your `opencode.json`:

```json
{
  "plugin": ["opencode-anthropic-oauth"]
}
```

---

## 🧠 Usage (Fix in 1 minute)

1. Run:
   ```
   /connect
   ```
   or:
   ```
   oc auth login
   ```

2. Select:
   ```
   Anthropic → Claude Pro/Max
   ```

3. Open the browser link  
4. Login to your Claude account  
5. Paste the code back into OpenCode  

✅ Done — your Claude models are working again

---

## 🛠️ How it works

- Implements OAuth PKCE flow
- Uses Anthropic auth endpoints
- Opens browser login (secure)
- Exchanges code for access + refresh tokens
- Stores tokens and refreshes automatically
- Sets required API headers

👉 Result: stable and working Claude access inside OpenCode

---

## 🔑 Working Methods

### ✅ Method 1 (Recommended — OAuth)
- Uses Claude Pro/Max subscription
- No API keys required
- Fixes invalid token errors
- Automatic token refresh

### ⚙️ Method 2 (Alternative — API)
- Use official Anthropic API keys
- More stable long-term
- Pay-as-you-go pricing
- No dependency on subscription

---

## ⚠️ Disclaimer

This plugin uses Anthropic’s public OAuth client.

Anthropic Terms of Service (February 2026) state that Claude Pro/Max subscription tokens should only be used with official clients.

👉 This is a community workaround  
👉 It may stop working at any time  

Use at your own discretion.

---

## 💬 SEO Keywords

- opencode invalid token fix  
- claude opencode not working  
- anthropic oauth workaround  
- fix claude authentication error  
- opencode claude pro max login  
- restore anthropic access  

---

## 📄 License

MIT
