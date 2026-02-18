# AI Solutions — Apresentação

Apresentação profissional sobre a jornada de criação da AI Solutions, desde a Tec2Go até soluções de IA para empresas portuguesas.

## 🚀 Como Usar

1. **Clone ou baixe este repositório**
2. **Adicione as suas imagens** na pasta `images/` com os nomes corretos (veja abaixo)
3. **Abra `index.html`** no navegador ou faça deploy no GitHub Pages

## 📸 Imagens Necessárias

Coloque as seguintes imagens na pasta `images/`:

- **`foto-perfil.jpg`** — Foto profissional/casual quadrada (~180x180px) para o slide 1
- **`tec2go-screenshot.jpg`** — Screenshot da loja Tec2Go ou Instagram (~500x280px, 16:9) para o slide 3
- **`perfil-instagram.jpg`** — Print/screenshot do teu perfil do Instagram para o slide 12

### Formato dos Nomes

Os arquivos devem ter exatamente estes nomes:
- `foto-perfil.jpg` (ou `.png`, `.jpeg`)
- `tec2go-screenshot.jpg` (ou `.png`, `.jpeg`)
- `perfil-instagram.jpg` (ou `.png`, `.jpeg`)

A apresentação detecta automaticamente se a imagem existe e a exibe. Se não existir, mostra um placeholder.

### 🏢 Logos das Empresas (Opcional)

Para o **carousel de logos** no slide 8, coloque os logos na pasta `images/logos/` com o formato:
- `1_nome_empresa.png` (o número define a ordem)
- `2_outra_empresa.jpg`
- etc.

Veja `images/logos/README.md` para mais detalhes.

## 🎯 Navegação

- **Setas do teclado** ← → ou **Espaço** — navegar entre slides
- **Clique** na metade esquerda/direita da tela — navegar
- **Toque** (mobile) — deslizar para navegar
- **Tecla F** — modo tela cheia

## 📁 Estrutura do Projeto

```
presentation-moneymasters/
├── index.html          # Landing page
├── presentation.html   # Apresentação principal
├── images/            # Pasta para suas imagens
│   ├── foto-perfil.jpg
│   ├── tec2go-screenshot.jpg
│   ├── perfil-instagram.jpg
│   └── logos/         # Logos das empresas (opcional)
│       ├── 1_ecodrive.png
│       ├── 2_fbeauty.png
│       └── ...
└── README.md          # Este arquivo
```

## 🌐 Ver a apresentação online (GitHub Pages)

Sim. Se subires o projeto para o GitHub e ativares o GitHub Pages, tens um **URL fixo** onde a apresentação fica sempre disponível, em qualquer dispositivo.

### Passo a passo

1. **Cria um repositório no GitHub**
   - Entra em [github.com](https://github.com) e clica em **New repository**
   - Nome sugerido: `presentation-moneymasters` (ou outro que queiras)
   - Deixa **Public** e não marques "Add a README" (já tens ficheiros no PC)
   - Clica em **Create repository**

2. **Envia o projeto do teu PC para o GitHub**
   - No terminal, na pasta do projeto (`presentation-moneymasters`), corre:
   ```bash
   git init
   git add .
   git commit -m "Apresentação AI Solutions"
   git branch -M main
   git remote add origin https://github.com/TEU-USERNAME/presentation-moneymasters.git
   git push -u origin main
   ```
   - Substitui `TEU-USERNAME` pelo teu nome de utilizador no GitHub e `presentation-moneymasters` pelo nome do repositório se tiveres usado outro.

3. **Ativa o GitHub Pages**
   - No repositório no GitHub: **Settings** → **Pages** (menu esquerdo)
   - Em **Source** escolhe **Deploy from a branch**
   - Em **Branch** escolhe `main` e pasta **/ (root)**
   - Clica **Save**

4. **Abre o URL**
   - Em 1–2 minutos o site fica no ar em:
   - **`https://TEU-USERNAME.github.io/presentation-moneymasters/`**
   - (ou `https://TEU-USERNAME.github.io/NOME-DO-REPO/` se o repositório tiver outro nome)

A partir daí podes abrir esse link no telemóvel, noutro PC ou partilhar com alguém — a apresentação aparece como está no repositório, sem precisares do teu PC.

## 📝 Personalização

Para alterar textos, edite diretamente o arquivo `presentation.html`. O CSS está incluído no mesmo arquivo para facilitar a manutenção.

## 🎨 Características

- Design moderno e profissional
- Totalmente responsivo
- Navegação intuitiva (teclado, mouse, touch)
- Animações suaves
- Modo tela cheia para apresentações
- **Carousel infinito de logos** no slide 8 (pausa ao hover)

---

**Criado por:** Josias Ponte  
**Para:** Apresentações sobre AI Solutions
