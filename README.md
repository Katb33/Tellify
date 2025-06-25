# Tellify – Tellonym Profile Humanifier  
#### Turns boring profiles into slightly less boring ones.

**Disclaimer**  
This project is for educational and showcase purposes only. It will not be released or maintained. I’m not responsible for any misuse.

---

## 🛠 What is Tellify?  
A fully requests-based, lightweight tool to bulk-modify Tellonym profiles—change avatars, names, and bios in seconds.

![Alt text](/ui.png)

---

## ✨ Features  
- ✅ Multi-threaded for speed  
- ✅ Optional proxy support  
- ✅ Avatar changer (random / sequence / custom)  
- ✅ Name changer (random / sequence / custom)  
- ✅ Bio changer (random / sequence / custom)  
- ✅ Token checker  
- ✅ Custom payload sender  
- ✅ Bonus: does monkey dance 🐒  

---

## ⚙️ How it Works  
- Reads from basic `.txt` files for tokens, names, bios, and proxies  
- Random or sequential mode for all changes  
- Uses threading for faster execution  
- All settings in `config.json` – edit easily  

---

## 📁 File Structure  
```
config.json        # Settings  
tokens.txt         # Your Tellonym tokens  
bios.txt           # List of bios  
names.txt          # List of names  
proxies.txt        # (Optional) proxies  
images/            # Avatar images (1.jpg, 2.jpg, ...)  
main.py            # Main script
```

---

## 🔒 Reminder  
Again, this tool is *not public* and intended for learning/showcase only.
