## 🦅 Model Overview
The **Texas Legal Eagle** by [Stonewire.co](https://stonewire.co) is a privacy-first Small Language Model (SLM) engineered specifically for Texas law firms. 

Every single step of this model's creation and deployment—from data collection to fine-tuning—was executed completely offline to guarantee zero data leakage, maximum security, and zero external bias.

## 🔒 The "Zero-Internet" Pipeline
We didn't just deploy locally; we *built* locally. 

* **Pure, Unbiased Data:** The foundational dataset was scraped directly from the official Texas statutes. No third-party editorializing, no hidden LLM biases—just the exact letter of the law.
* **Air-Gapped Data Generation:** All instruction-response training pairs were generated entirely within a secure, local network leveraging local models like Gemma. Not a single byte of training data was ever sent to OpenAI, Anthropic, or the public internet.

## ⚙️ Architecture & Commercial Safety
* **Base Model:** Built on top of Microsoft's **Phi** architecture. 
* **Why Phi?:** Selected for its extremely efficient parameter-to-performance ratio and its permissive **MIT License**, guaranteeing law firms the utmost privacy, flexibility, and commercial safety without vendor lock-in.
* **The Engine:** A highly targeted, proprietary DoRA (Weight-Decomposed Low-Rank Adaptation) trained exclusively on Texas legal codes.

## 💻 Consumer-Grade Hardware Deployment
Secure AI shouldn't require a data center. Because the Texas Legal Eagle is a highly optimized SLM, it is tested and verified to run flawlessly on **consumer-grade hardware**. 

* **Zero IT Bloat:** Completely eliminates the need for 5- or 6-figure enterprise server deployments.
* **Plug and Play:** Runs natively on a firm's existing high-end workstations or a single, affordable local machine.
* **Cost Certainty:** Flat-rate deployment with absolutely zero recurring API token costs.

## 🛑 Access (Closed Source)
**This repository does not contain the model weights or the proprietary DoRA dataset.** Due to the strict privacy requirements of legal compliance, this model is exclusively deployed as an on-premise "Legal Node." 

To request a secure deployment for your firm, visit [Stonewire Legal Nodes](https://stonewire.co/legal-nodes/texas-legal-eagle).
