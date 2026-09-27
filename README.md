# Hack-The-Box-Writeups
Kumpulan write-up dari beberapa **Hack The Box machine** yang pernah saya kerjakan.

Di sini saya dokumentasikan prosesnya dari awal, mulai dari **enumeration, cari vulnerability, exploitation, sampai privilege escalation**. Selain nulis langkah-langkahnya, aku juga masukin beberapa hal yang aku pelajari selama ngerjain masing-masing machine.

## Machines

### Expressway — Easy

Machine Linux yang fokusnya banyak di **network enumeration, IPsec/IKE, credential discovery**, dan privilege escalation.

**Topics:**

* Nmap
* UDP & IPsec enumeration
* IKE aggressive mode
* PSK cracking
* SSH
* Sudo exploitation
* Privilege escalation

Write-up ini ngejelasin proses dari initial enumeration sampai berhasil mendapatkan root access.

---

### Guardian — Hard

Guardian punya alur yang lebih panjang dan cukup banyak layer. Selama ngerjain machine ini, ada beberapa vulnerability yang ketemu di web application dan proses authentication.

**Topics:**

* Network & web enumeration
* Information disclosure
* Default credentials
* Authentication bypass
* Gitea & source code analysis
* XSS
* Cookie/token extraction
* CSRF token replay
* LFI
* PHP filter chains
* Privilege escalation

Machine ini juga melibatkan custom API, JWT, dan beberapa vulnerability yang perlu dianalisis dari source code sebelum bisa lanjut ke tahap berikutnya.

---

## What I Practiced 🔍

Beberapa hal yang saya pelajari dan praktikkan dari machine-machine ini:

* Reconnaissance & Enumeration
* Web Application Security
* Linux Privilege Escalation
* Authentication & Session Security
* XSS & Injection
* LFI
* Source Code Analysis
* CVE Research
* Exploitation

## Disclaimer

Semua write-up di sini dibuat untuk **learning & educational purposes** dan dikerjakan di environment Hack The Box yang memang disediakan untuk latihan.

Don't use these techniques on systems you don't have permission to test.

---

*More write-ups coming soon...* 🚀
