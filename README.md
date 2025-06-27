# 🧹 Pulizia File Temporanei Windows

**Pulizia automatica di file temporanei e cache del sistema e dei browser su Windows**, con supporto per backup, esclusioni e aggiornamento automatico.

---

## ✨ Funzionalità principali

- 🧼 Pulisce le cartelle:
  - `C:\Users\<utente>\AppData\Local\Temp`
  - `C:\Windows\Temp`
  - `C:\Windows\Prefetch`
  - `C:\Windows\SoftwareDistribution\Download`
  - Cache di Chrome, Firefox, Edge
- 💾 Backup ZIP automatico prima della cancellazione
- 🛡️ Supporto per esclusione cartelle specifiche
- 📁 Aggiunta cartelle personalizzate
- 📜 Log completo e esportabile
- ♻️ Sistema di auto-aggiornamento integrato (via GitHub)
- 👀 Interfaccia grafica chiara con emoji e pulsanti grandi

---

## 🔧 Requisiti

- Windows 10 o superiore
- Python 3.8+ (se usato come script)
- Permessi da amministratore
- Internet attivo per controllare aggiornamenti

---

## 🚀 Avvio rapido

### 👉 Come script Python

```bash
python pulizia_temp_gui.py
