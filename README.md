# E-commerce Order Management and Logs

A simple Linux-based project that demonstrates how to manage and track e-commerce orders using shell commands and Git.

## 📁 Project Structure
```
orders/
├── pending/             # Stores new/pending orders
├── completed/           # Contains completed orders
├── logs/                # Logs movement and disk usage
├── .gitignore           # Excludes backups (*.tar.gz)
└── completed_backup.tar.gz (ignored)
```
---

## ⚙️ Features
- 📦 Create, move, and track order files
- 🕓 Maintain movement logs with timestamps
- 🗜️ Compress completed orders into backup archives
- 💾 Record and analyze disk usage data
- 🧩 Follow a professional Git workflow (branching, commits, PRs)

---

## 💻 Linux Commands Used
```bash
mkdir -p /var/orders/{pending,completed,logs}
mv pending/order1.txt completed/
tar -czf completed_backup.tar.gz completed/
du -h /var/orders > logs/usage.txt
echo "$(date +'%Y-%m-%d') - order moved" >> logs/movements.log
```  

---

## 👨‍💻 Author
**Aditya Chouksey**  
[GitHub Profile](https://github.com/adityaa099)
