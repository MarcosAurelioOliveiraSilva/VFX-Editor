# 🌌 VFX Editor — Professional Visual Effects & Shading Studio

O **VFX Editor** é uma ferramenta desktop de nova geração desenvolvida em Electron e WebGL (React Three Fiber), projetada especificamente para simplificar a criação, manipulação e exportação de efeitos visuais avançados, shaders e simulações de partículas para jogos.

---

## 🚀 Recursos de Destaque (VFX & Materiais)

* **🎨 Estúdio de Efeitos Completamente Interativo**
  * Visualização 3D em tempo real com controle total de câmera (OrbitControls com limites inteligentes de Zoom, Pan e Rotação).
  * Gizmos de transformação integrados (Translação, Rotação e Escala) para controle preciso de emissores, portais e malhas.

* **🧠 Inteligência Artificial Integrada (AI Texture Generator)**
  * Sistema nativo de prompts para gerar mapas de ruído (Noise Maps), mapas de opacidade e texturas procedimentais via IA, aplicando-as instantaneamente nos canais de materiais do seu efeito.

* **🎬 Animação 3D & Rigging System (FBX/GLTF)**
  * Importação direta de personagens com suporte a esqueletos complexos (`SkinnedMesh`).
  * Visualizador de articulações (`SkeletonHelper`) e sistema de sockets para acoplar emissores de partículas a ossos específicos (ex: mãos, armas) em tempo real durante as animações.

* **🎵 Áudio Reativo Avançado**
  * Analisador de espectro de áudio integrado (`AudioAnalyser`). Faça a intensidade do Bloom, a velocidade do Vortex e a emissão de partículas pulsarem em sincronia com arquivos `.MP3` ou `.WAV`.

* **💾 Integração Nativa & Auto-Save**
  * Manipulação direta de arquivos do sistema operacional via Electron FS (Salvar, Carregar e Abrir Projetos).
  * Sistema automático de salvamento em background (Auto-Save) para prevenção de perda de dados.

---

## 📦 Notas de Instalação (Windows)

1. Baixe o instalador executável na seção de **Assets** abaixo: `VFX Editor Setup 1.0.0.exe`.
2. Execute o arquivo e siga o assistente de instalação na tela (com criação automática de atalhos na Área de Trabalho).
3. *(Alternativo)* Se preferir rodar sem instalação, faça o download da versão portátil `.zip`, extraia o conteúdo e execute o arquivo principal.

---

## 🛠️ Requisitos Técnicos de Exportação

O ecossistema gera uma saída limpa e padronizada em dados estruturados, pronta para integração imediata em pipelines de produção:
* **Unity:** Compatível com Particle System e nós do VFX Graph.
* **Unreal Engine:** Estruturado para o sistema Niagara.
