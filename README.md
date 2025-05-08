# 🔍 dnsbrute — DNS Subdomain Brute Forcer em C

Um script simples em C para força bruta de subdomínios DNS usando uma wordlist.

---

## 📦 Requisitos

- GCC (compilador C)
- Linux, macOS ou Windows com suporte a sockets BSD (Linux recomendado)
- Conexão com a internet

---

## 🛠️ Instalação

1. **Clone ou baixe o código-fonte:**

```bash
git clone https://github.com/seu-usuario/dnsbrute.git
cd dnsbrute
```

2. **Compile o código:**
```bash
gcc dnsbrute.c -o dnsbrute
```

3. **Uso:**
```bash
./dnsbrute <domínio> <wordlist.txt>
```

## Exemplo de uso
```bash
>> ./dnsbrute google.com wordlist.txt 
[+] Testando kill.google.com
    [>]kill.google.com -> Nao encontrado
[+] Testando jaon.google.com
    [>]jaon.google.com -> Nao encontrado
[+] Testando chain.google.com
    [>]chain.google.com -> Nao encontrado
[+] Testando brs.google.com
    [>]brs.google.com -> Nao encontrado
[+] Testando imghp.google.com
    [>]imghp.google.com -> Nao encontrado
[+] Testando mail.google.com
    [>] mail.google.com -> 142.251.128.165
```