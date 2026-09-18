## 🧪 Cenários de Testes Windows (Sysmon + MITRE ATT&CK)

### 1. Deteção de Persistência no Registo (MITRE T1547.001)
* **Ação:** Criação de uma chave maliciosa na diretoria `Run` do Windows através do PowerShell.
* **Evidência do Sysmon:** Captura de alteração de Registo (Event ID 13).
* **Alerta Wazuh:** Identificado como tática de persistência com criticidade média/alta.

### 2. Deteção de Reconhecimento/Acesso a Credenciais
* **Ação:** Tentativa de leitura de chaves SAM/SYSTEM via CLI.
* **Alerta Wazuh:** Alerta imediato sobre comandos suspeitos executados por utilizadores não-admnistradores.# urban-waddle
