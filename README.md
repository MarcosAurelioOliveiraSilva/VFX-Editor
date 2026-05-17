# 🎮 SA-MP Server Dashboard & Controller

Um painel de controle desktop de alta performance desenvolvido para simplificar a administração, edição e monitoramento em tempo real de servidores San Andreas Multiplayer (SA-MP). Chega de gerenciar arquivos por scripts bat ou logs manuais.

---

## 🚀 Funcionalidades Principais

### ⚡ Automação & Controle do Servidor
* **Inicialização Inteligente:** Botão Power de um clique para ligar/desligar o processo `samp-server.exe` de forma limpa.
* **Sistema de Trava de Segurança:** O botão de inicialização permanece bloqueado caso a estrutura de diretórios obrigatória do SA-MP não seja validada, prevenindo crashes no sistema operacional.
* **Persistência de Diretório:** Seleção inteligente da pasta raiz do servidor com salvamento automático de caminhos e estados.

### 📟 Monitoramento Ativo (Live Diagnostics)
* **Console com Live Stream:** Captura e renderização em tempo real de todo o output de texto do terminal do servidor dentro do app.
* **Protocolo SA-MP Query:** Sistema nativo via comunicação UDP para puxar métricas exatas diretamente da porta do servidor.
* **Telemetria Avançada:** Contador de jogadores online, monitoramento de Ping (latência) constante e cronômetro de Uptime em tempo real.

### ⚙ Gestão de Configurações & Segurança
* **Editor Sincronizado de `server.cfg`:** Interface híbrida contendo inputs de campos rápidos para configurações críticas (RCON, MaxPlayers, Port) e um editor em modo RAW para controle total das linhas.
* **Validação de Arquivos:** Scanner automático na primeira execução para checar a integridade e presença de componentes essenciais.
* **Onboarding Comercial:** Tela integrada de Termos de Uso (EULA) com aceite obrigatório persistido localmente antes da liberação do painel.

---

## 🎨 UI/UX Moderna
* **Interface Dark Mode:** Visual escuro focado no conforto visual prolongado de desenvolvedores e administradores.
* **Barra de Status Dinâmica:** Feedback visual instantâneo (cores e animações fluidas) sobre a saúde e conectividade do processo em background.
