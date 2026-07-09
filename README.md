# Minecraft Raylib C++

Um clone de Minecraft desenvolvido do zero em **C++**, utilizando a biblioteca **Raylib** para renderização gráfica e gerenciamento de inputs. O projeto foca em desempenho, modularidade e fidelidade técnica às mecânicas clássicas de sandbox voxel.

---

## 🚀 Funcionalidades

### 🎮 Modos de Jogo
* **Singleplayer:** Explore, construa e destrua blocos em um mundo local persistente.
* **Multiplayer:** Conecte-se a servidores para jogar com amigos em tempo real (arquitetura cliente-servidor).

### 🌍 Gerenciamento de Mundo & Performance
* **Renderização Baseada em Chunks:** O mundo é dividido em pedaços dinâmicos (chunks) carregados e descarregados em tempo real ao redor do jogador para otimizar o uso de memória e processamento.
* **Armazenamento Otimizado:** Os mundos **não** utilizam o formato `.dat`. Em vez disso, foi implementado um sistema próprio e customizado de salvamento de chunks, garantindo leitura e escrita rápidas no disco.

### 🎨 Customização
* **Suporte a Resource Packs:** Altere completamente o visual do jogo! O sistema carrega texturas e elementos visuais externamente através de pacotes de recursos customizados.
### 📗 Bibliotecas e ações precisas
* **MSYS2, adicionar MSYS2 para o PATH do Windows** *
---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** C++ (g++ / padrão moderno)
* **Biblioteca Gráfica:** [Raylib](https://www.raylib.com/)
* **Compilador/Ambiente Recomendado:** MSYS2 (g++)

---

## 📦 Estrutura de Pastas (Principal)

```text
├── Content/                  
│   ├── worlds/            
│   ├── resource-packs/          
│   └── fonts/           
├──  .cmdmc
└── minecraft.exe
