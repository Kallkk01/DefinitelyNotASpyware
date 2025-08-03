## DefintelyNotASpyware.bat                                                
*A humble Python keylogger… with potential for much more.*

---

## 👀 About the Project  
This repository contains a simple, cross-platform keylogger built using Python and `pynput`.

It’s a barebones prototype — a *proof of concept*, not a weapon. Designed for experimentation, curiosity, and ethical exploration. If you're into stealth tooling, data exfiltration theories, or just enjoy poking the edges of what Python can do, you’re in the right place.

That said…

> ⚠️ **This is a basic keylogger. You will almost certainly fail if you try to “log a victim” with this paper knife.**  
> Modern antivirus software (even Windows Defender) will spot you walking naked from miles away. This is a research tool — not a stealth-grade implant.

---

## ✅ Features (Current)
- Captures keystrokes in the background
- Auto-saves logs locally
- Runs silently (sort of)
- ~10 lines of Python that’ll make you feel like a wizard

---

## 💡 Future Directions (Purely Hypothetical)
This project is a seed. You could grow it into something… else. Just saying.

- Scheduled screenshots (encoded into images?)
- Filename obfuscation and stealth startup registration
- Encrypted log dumping
- Cloud sync or API-based reporting
- Stego transport: keyboard logs inside an innocent-looking cat meme
- Sandbox detection or AV evasion logic

Not implemented — just things that make the brain itch.  

---

## 📁 Files Included
| File | Purpose |
|------|---------|
| `keylogger.py` | Main script |
| `README.md` | This file you're reading |
| `.gitignore` | Keeps garbage out of your repo |
| `LICENSE` | MIT — take it, tweak it, break it (ethically) |

---

## 🚀 Getting Started

> ⚠️ This is for local testing in a controlled environment. Don’t run this on production systems or others' machines.

### 1. Clone the repo:
```bash
git clone https://github.com/yourusername/DefinitelyNotSpyware.bat.git
cd DefinitelyNotSpyware.bat

### 2. Install the dependency:
This script requires pynput for keyboard event monitoring.

pip install -r requirements.txt

### 3. Run the script:

python keylogger.py
