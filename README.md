# Pi-50b-digits
50 billion digits of π (Pi) computed using y-cruncher on a low-resource system

This repository documents the computation of **50 billion digits of π (Pi)**, in both decimal and hexadecimal formats.

# 📦 Download Dataset

You can download the full dataset (compressed `.zst` files) from the [Internet Archive](https://archive.org/details/pi-decimal-50-b).

### Files included:
- Pi-Decimal-50B.zst
- Pi-Hex-50B-balanced.zst
- Validation file: `Pi-20250709-050330.txt`
- Full terminal logs

## 🧠 Computation Details

- **Algorithm**: Chudnovsky
- **Software**: `y-cruncher v0.8.6.9545` (Swap Mode)
- **Time taken**: ~47 hours
- **System**:
  - Intel i5-11400H (6 cores)
  - 8GB RAM + 32GB Swap (ZRAM disabled)
  - Pop!_OS Linux

## 🧪 Verification

See [`verification/`](./verification) for terminal logs and validation.

## 📄 License : 

 MIT 

## ✍️ Author

Srijan Das  
Email: srijandas008@gmail.com

