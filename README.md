# Coral Lineage Standard (CLS) v1.0

The Coral Lineage Standard (CLS) is a vendor-neutral, certifiable specification for tracking, validating, and sharing coral lineage data across auction platforms, online marketplaces, and personal websites. It allows coral sellers and buyers to build trust through verified lineage transparency.

---

## 🧬 Purpose

This schema ensures:
- **Interoperability** across platforms like SaltyBid, eBay, and Shopify
- **Lineage integrity** for coral collectors and sellers
- **Transparency** of ownership history and frag origin
- **Integration** into certificates, QR tags, and real-time validators

---

## 📦 Key Fields

- `clid`: Unique Coral Lineage ID (UUID-based or hashed)
- `coralName`: Named strain (e.g., Jason’s Rainbow Mille)
- `strainOrigin`: First source (wild or aquacultured)
- `lineageChain[]`: Array of ownership events
- `gen`: Generation number from mother colony
- `verifiedBy[]`: Certifying organizations
- `traits[]`: Optional metadata about coral color, structure, etc.
- `images[]`: Coral imagery over time
- `qrCodeURL`: Verifiable link to public certificate
- `signature`: Optional cryptographic signature for authenticity

---

## ✅ JSON Schema

The official schema file is available here:
- [CLS_v1.0_schema.json](CLS_v1.0_schema.json)
- [CLS_v1.0_schema.yaml](CLS_v1.0_schema.yaml)

---

## 🔒 Certification Authority

SaltyBid serves as the primary certification authority (CA), providing:
- Certificate validation services
- Verified lineage assignment
- API for QR code lookups

---

## 💡 Use Cases

- Coral auctions (SaltyBid, eBay, forums)
- Physical coral frag tags (QR-linked)
- Digital lineage certificates
- Storefront badges

---

## 🚀 Future Versions

Planned improvements:
- NFT/Tokenized lineage options
- On-chain verification (optional)
- Dispute resolution mechanisms
- Lineage health or growth trait indexing

---

© 2025 SaltyBid.com | All Rights Reserved.
