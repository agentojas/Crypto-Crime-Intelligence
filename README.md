# Crypto Exchange Enumeration for Investigation Leads

A simple OSINT technique to help investigators identify which cryptocurrency exchange a suspect may be using, starting with nothing more than a phone number.

---

# The Problem

In many cryptocurrency-related investigations—such as online scams, money laundering, or terror financing—investigators often possess only limited information about the suspect, typically a mobile phone number.

However, they usually do **not** know:

- Which cryptocurrency exchange the suspect uses
- Which exchange should receive a legal notice or preservation request
- Where to begin tracing the suspect's crypto assets

The traditional approach is to send legal notices to multiple exchanges and wait for responses. This process is slow, resource-intensive, and often results in unnecessary requests to exchanges where the suspect has no account.

---

# The Idea

Instead of contacting every exchange, investigators can first determine which exchanges recognize the suspect's phone number during the public registration process.

This allows investigators to create a shortlist of relevant exchanges before initiating formal legal procedures.

---

# How It Works

Many cryptocurrency exchanges check whether a phone number is already registered during account creation to prevent duplicate accounts.

This behavior can be used to narrow investigative leads.

## Step 1

Obtain the suspect's mobile number from:

- Victim complaint
- NCRP report
- Intelligence input
- Other lawful investigative sources

---

## Step 2

Visit the exchange's public registration page.

---

## Step 3

Enter the suspect's phone number as if creating a new account.

---

## Step 4

Observe the exchange's response.

### Registered Number

The exchange displays messages similar to:

```
Phone number already registered
```

or

```
Account already exists
```

This suggests the suspect likely has an account on that exchange.

---

### Not Registered

The registration process continues normally (typically requesting an OTP without displaying an "already registered" error).

This suggests the phone number is not currently registered on that exchange.

---

## Step 5

Repeat the process across multiple exchanges.

---

## Step 6

Create a shortlist of exchanges where the phone number appears to be registered.

---

## Step 7

Send legal notices, preservation requests, or KYC requests **only** to the shortlisted exchanges.

This transforms a broad, trial-and-error process into a focused investigative workflow.

---

# Supported Exchanges

The methodology has been documented for the following centralized cryptocurrency exchanges:

- Binance
- KuCoin
- ZebPay
- Mudrex
- CoinSwitch
- Giottus
- UnoCoin
- SunCrypto
- Delta Exchange
- WazirX

For each exchange, the project documents:

- Registration URL
- Required input fields
- Response indicating an existing account
- Response indicating a new account

---

# Advantages

- Reduces unnecessary legal notices
- Saves investigation time
- Helps prioritize exchanges
- Provides faster investigative leads
- Uses only publicly accessible registration workflows

---

# Intended Use

This methodology is intended for:

- Law Enforcement Agencies
- Cyber Crime Investigation Units
- Financial Intelligence Investigators
- Authorized Digital Forensics Professionals

It is **not** designed as a general-purpose lookup tool.

The technique relies solely on information exposed through an exchange's normal public registration flow.

No authentication bypass, exploitation, vulnerability, or unauthorized access is involved.

---

# Important Note

This technique only helps identify **potential** exchanges associated with a phone number.

It **does not** reveal:

- Wallet addresses
- Transaction history
- KYC information
- Balances
- Personal information

Any subscriber information or account details must still be obtained through the appropriate legal process (such as a subpoena, legal notice, court order, or preservation request), in accordance with applicable laws and the exchange's procedures.

---

# Disclaimer

This project is intended solely for:

- Educational purposes
- Security research
- Lawful OSINT investigations
- Authorized law enforcement activities

Users are responsible for ensuring compliance with all applicable laws, regulations, and the terms of service of the relevant cryptocurrency exchanges.

---

# Author

**AgentOJAS**
