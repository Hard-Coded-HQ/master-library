# 8% Summary: IPFS Gateways & Pinning

## 1. The Big Problem with IPFS
When you upload a file to IPFS from your phone or computer, your device becomes the "host." If you turn off your phone or close your internet browser, your file disappears from the network. Nobody else can see it.

## 2. The Solution: Pinning Services
To keep your files online 24/7 for free, you use a **Pinning Service**. These are massive cloud servers running IPFS nodes that stay turned on forever. They grab your file and "pin" it down so it never gets deleted.
* **Popular Free Service:** Pinata (gives you free space to host your files).

## 3. How to View Your Files: Gateways
Standard web browsers (like Chrome or Safari) cannot read IPFS links directly. They don't understand web3 addresses. 
To fix this, we use an **IPFS Gateway**. A gateway is a bridge website that takes an IPFS file and forces it to show up on a normal web browser.

* **Normal Web Link via Gateway:** `https://ipfs.io/ipfs/YOUR-FILE-CID-HERE`

## 4. Short Summary
To make a permanent, free website:
1. Upload your code files to a free service like Pinata.
2. Get your unique file CID code.
3. Share your Gateway link so anyone in the world can open your site on a normal phone or PC.
4. 
