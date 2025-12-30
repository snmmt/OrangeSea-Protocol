# 🍊 Project OrangeSea: The Sovereign Network State

> **Status:** Phase 0 (Prototyping)
> **Contact (Dev):** orangesea.project@proton.me
> **Contact (General):** contact@orangesea.org
> **Website:** [orangesea.org](https://orangesea.org)

---

## 👋 A Letter to Potential Co-Founders

**I am not a professional programmer.**
I am a **Credit Risk Officer** with 10 years of experience in the banking industry, specializing in risk control models and credit assessment.

**Why am I here?**
I have witnessed the fragility of centralized credit systems and the suppression of digital freedom. I believe that the next generation of the internet needs a **financial-grade trust system** built on top of a censorship-resistant network.

I have designed **OrangeSea**—not just as another chat app, but as a **Mandatory Contribution Mesh Network** with a rigorous economic model derived from real-world banking logic.

I bring the **Vision**, the **Risk Models**, and the **Product Strategy**.
I am looking for **Rust / P2P Engineers** to bring the **Code**.

---

## 🏗️ What is OrangeSea?

OrangeSea is an **Overlay Network** (Chat-VPN) built on top of the existing internet. It enforces a "No Free Riders" policy to ensure network resilience.

### 1. Unified Client & Mandatory Contribution
- **One App, All Nodes:** No distinction between servers and clients.
- **VPN as a Service:** The mobile client (iOS/Android) requests system-level VPN permissions upon launch.
- **The Slider of Duty:** Users cannot turn off contribution. They can only adjust the slider:
  - 🟢 **Eco:** Minimum heartbeat. No Token reward.
  - 🔴 **Overdrive:** Max bandwidth contribution. Max Token reward.

### 2. Dual-Track Economy (The Innovation)
To prevent capital monopoly (Sybil Attacks), we strictly separate **Profit** from **Honor**.

| Metric | **Tinder Token (Fuel)** | **Reputation Score (Soul)** |
| :--- | :--- | :--- |
| **Source** | Physical Contribution (Bandwidth/Storage) | Social Behavior & Contract Fulfillment |
| **Tradeable?** | ✅ Yes | ❌ **No (Soulbound)** |
| **Use Case** | Payment, Exchange | Governance, **Visa Application** |

### 3. Sybil Resistance: The "Credit Ramp"
Based on banking logic:
- **New Accounts = Zero Credit:** A new node with 0 Reputation has a Token Yield Coefficient of ≈ 0.
- **Social Proof:** To earn tokens, a node must prove it is human by establishing connections in the **Web of Trust**.
- **Result:** Bot farms are economically unviable.

---

## 🛠️ Technology Stack (Target)

We are looking for expertise in the following areas:

- **Core:** Rust (Libp2p, Tokio, QUIC).
- **Mobile Network:** iOS `NetworkExtension` (PacketTunnelProvider), Android `VpnService`.
- **Discovery:** DHT (Kademlia), MDNS, Bluetooth LE / Wi-Fi Direct (for local mesh).
- **Privacy:** ZK-SNARKs (for Identity/Reputation proof).

---

## 🤝 Roles We Are Recruiting

We are looking for **Founding Engineers** who want to build a digital nation, not just an app.

### 1. Core Protocol Engineer (Rust)
- **Mission:** Implement the P2P traffic control algorithm (The Slider Logic) and the Libp2p communication layer.
- **Requirement:** Deep understanding of async Rust and networking protocols.

### 2. Mobile Platform Engineer (iOS/Android)
- **Mission:** Keep the connection alive. Hack the `NetworkExtension` and background tasks to create a persistent VPN tunnel.

### 3. Zero-Knowledge Researcher
- **Mission:** Build the bridge between on-chain reputation and real-world identity (Visa) without revealing user data.

---

## 🚀 How to Join

If you are interested in building this **Mandatory Mesh Network** with me:

1.  Read our [Website](https://orangesea.org) for the full vision.
2.  Email me at **orangesea.project@proton.me** (PGP Key available upon request).
3.  Or verify yourself by starring this repo and opening an Issue titled **"I am a Node"**.

Let's build the fire. 🔥
