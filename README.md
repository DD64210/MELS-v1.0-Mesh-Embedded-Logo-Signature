# MELS v1.0 – Mesh‑Embedded Logo Signature

**MELS (Mesh‑Embedded Logo Signature)** is an open method for embedding a logo directly into the geometry of a 3D model.  
It provides a structural, geometry‑based signature that remains independent of textures, materials, or metadata, and is fully compatible with **glTF/glb** formats for interactive 3D NFTs.

This repository contains the official **MELS v1.0 Technical Short Specification (PDF)**.

---

## 📘 What is MELS?

MELS defines a simple and reproducible process:

- A logo is modeled as a **3D object** (not a texture).  
- The logo is **added, subtracted, or embedded** into the host mesh using geometric operations.  
- The final model is exported as **glTF/glb** to function as an interactive 3D NFT.  
- The signature exists **inside the mesh itself**, making it durable, portable, and independent of metadata.

MELS is an **open method**, released under **CC0 (public domain)**.  
Anyone may use it freely, commercially or non‑commercially.

---

## 🧩 Minimum Requirements for MELS Compliance

A 3D NFT is considered MELS‑compliant if:

1. The logo is a **3D object**, not a texture.  
2. The logo is **geometrically integrated** into the host mesh.  
3. The final model is exported or converted to **glTF/glb**.  
4. The integration is **intentional** and part of the artistic process.

Full details are available in the PDF.

---

## 🛑 Constraints

The following are **not** considered MELS:

- Texture‑based logos (UVs, decals, watermarks, overlays)  
- Signatures present only in metadata  
- Logos added in non‑geometric post‑production  
- Use of protected logos or trademarks without proper rights  
- A single crypto wallet may contain **only one** MELS logo‑signature  
- Companies or agencies must use **separate wallets** for each identity they represent  

MELS does **not** replace traditional legal protections (copyright, trademarks, institutional filings).

---

## 🟦 Historical Prototype — *Bad Head Cyan (2022)*

The first documented example of the MELS method is:

**Bad Head Cyan (2022)**  
- Mint date: **February 3, 2022**  
- Contract Address: `0x495f947276749Ce646f68AC8c248420045cb7b5e`  
- Token ID:  
  `25584371751761932873858142294993948590275096702038761411014667971760299704321`

This NFT predates the formal naming and publication of the method and serves as the **historical prototype** of MELS.

---

## 📄 License

MELS v1.0 is released under **CC0 (Public Domain)**.  
You may use, modify, redistribute, or implement the method freely.

---

## ⚖️ Responsibility & Legal Framework

Users are solely responsible for:

- respecting intellectual property rights,  
- complying with local and international laws,  
- ensuring proper use of logos and trademarks.

The author of MELS declines all responsibility for misuse or legal violations.

---

## 📎 Files in this Repository

- **MELS-v1.0.pdf** — Official Technical Short Specification  
