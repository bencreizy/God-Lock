# God Lock 🔒

**Project Omega: Void Handshake** - A cyberpunk-themed encryption interface with 3D cryptex tumblers and vault mechanism.

![God Lock Interface](https://img.shields.io/badge/Status-Live-00f0ff?style=for-the-badge)

## 🌌 Features

- **3D Cryptex Tumblers** - Interactive rotating digit wheels with cinematic animations
- **Omega Vault Mechanism** - 8-arm vault assembly with locking/unlocking animations
- **Advanced Encryption** - Custom cipher using vector matrix keys (15-digit combinations)
- **Cyberpunk UI** - Animated starfield, scanlines, and glowing cyan aesthetics
- **File Support** - Upload and encrypt/decrypt text files
- **Keyboard Navigation** - Press Enter to cycle through X→Y→Z axes
- **Custom Scrollbar** - Interactive draggable scroll indicator

## 🚀 Live Demo

[View Live Demo](https://your-deployment-url.vercel.app)

## 🎮 How to Use

1. **Enter Vector Keys**
   - Click on X, Y, or Z axis
   - Type 5 digits (e.g., 12345)
   - Press Enter to move to next axis
   - Repeat for all three axes (15 digits total)

2. **Encrypt/Decrypt**
   - Click the pulsing Ω loader to activate terminal
   - Type or paste your text
   - Click the Omega vault to LOCK (encrypt)
   - Click again to UNLOCK (decrypt) with same keys

3. **File Operations**
   - Click the + button to upload text files
   - Encrypt/decrypt file contents
   - Copy encrypted output for secure storage

## 🛠️ Technical Details

- **Pure HTML/CSS/JavaScript** - No dependencies
- **Custom Cipher Algorithm** - FNV-1a hash-based key derivation
- **Noise Mapping** - 1:1 character substitution with UNIQUE_NOISE string
- **Responsive Design** - Scales for mobile, tablet, and desktop
- **Performance Optimized** - Hardware-accelerated animations

## 📦 Deployment

### Vercel (Recommended)
```bash
vercel --prod
```

### Manual Deployment
1. Clone this repository
2. Deploy `index.html` to any static hosting service
3. No build process required!

## 🔐 Security Note

This is a demonstration encryption interface. For production use cases requiring strong cryptographic security, please use established encryption libraries like AES or RSA.

## 📄 License

MIT License - Feel free to use and modify!

## 🎨 Credits

- Starfield animation inspired by Uiverse.io
- Omega logo from God Lock project
- Created with cyberpunk aesthetics in mind

---

**Made with 🌌 by the Void**
