#  Menu de Segurança do Sistema (Windows) – BAT Puro

Ferramenta educacional desenvolvida em Batch Script (BAT) para análise básica de rede e reforço de segurança do Windows, funcionando totalmente em modo offline.

Criado por: Claudio Almeida

---

## 📌 Funcionalidades

- Ping e Traceroute com validação anti-injeção
- Scan de host e rede local com Nmap
- Listagem de redes Wi-Fi próximas
- Geração de hash SHA256 de arquivos
- Listagem de portas abertas
- Execução do MSRT (Microsoft Malicious Software Removal Tool)
- Hardening (reforço de segurança do sistema):
  - Ativação do Firewall
  - Scan do Windows Defender
  - SFC e DISM
  - Desativação do SMBv1

---

## 🔐 Segurança

O projeto implementa:

- Validação anti-injeção de comandos
- Bloqueio de caracteres perigosos: `& | < > %`
- Execução somente com privilégios de administrador

---

## ⚙️ Requisitos

- Windows 10 ou superior
- Executar como administrador
- Nmap (opcional para scans de rede)

---

## ▶️ Como usar

1. Baixe o arquivo `.bat`
2. Clique com botão direito → Executar como administrador
3. Use o menu interativo

---

## ⚠️ Aviso legal

Este projeto é para fins educacionais e de estudo de segurança defensiva (blue team).

Não me responsabilizo por uso indevido.

---

## 📜 Licença

MIT License 

Antes de explorar uma falha, pense em quem está do outro lado.

---

## ⭐ Contribuições

Sugestões e melhorias são bem-vindas!
