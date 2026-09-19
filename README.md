# Oraculo-Zefiro

# ✹ Oráculo Zéfiro - Guru Místico & Astral

> Um santuário oracular interativo hospedado diretamente no **GitHub Pages**, alimentado pela API do **Google Gemini** para leituras personalizadas de Tarot, Búzios, Horóscopo, Runas e artes esotéricas ancestrais.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini%20API-8E75B2?style=flat&logo=google&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=githubpages&logoColor=white)

---

## ✨ Funcionalidades Principais

- **🏛️ Fluxo em 2 Etapas:**
  1. **Santuário dos Portais:** Tela inicial com painel completo de consultas e a **Roleta do Destino** para sorteio aleatório de rituais.
  2. **Câmara Astral de Zéfiro:** Chat direto com o guru místico, formatado com suporte a Markdown, citações e respostas poéticas.
- **🔮 15+ Práticas e Oráculos Interativos:**
  - **Tarot:** Tiragem com carta 3D animada (*flip card*) dos Arcanos Maiores.
  - **4 Búzios Sagrados:** Sorteio dinâmico das conchas com cálculo tradicional de *Odùs* (*Aláfia, Ejife, Etawa, Okanran, Oyekun*).
  - **Horóscopo do Dia:** Consulta aos 12 signos zodiacais com conselho e cristal do dia.
  - **Runas Nórdicas:** Sorteio de símbolos ancestrais (*Futhark*).
  - **Baralho Cigano (Lenormand):** Tiragem de 3 cartas (Passado, Presente e Futuro).
  - **I Ching:** Hexagramas do Livro das Mutações com base nas 3 moedas.
  - **Respostas Diretas:** Bola de Cristal, Pêndulo Sagrado (Radiestesia), Cafeomancia e Biscoito Cósmico.
  - **Equilíbrio Energético:** Harmonização dos 7 Chakras, Invocação de Arcanjos Protetores, Banhos de Ervas e Decifrador de Sonhos.
- **🔔 Áudio Imersivo:** Síntese sonora de Tigela Tibetana / Frequências Solfeggio (432Hz e 528Hz) diretamente via Web Audio API (sem arquivos externos pesados).
- **🛡️ Alta Resiliência (Anti-Erro 503):** Sistema com fallback automático entre modelos Gemini (`gemini-1.5-flash`, `gemini-2.0-flash`, `gemini-1.5-pro`) para contornar sobrecargas temporárias de servidor.
- **🔒 Privacidade & Segurança:** Nenhuma chave de API fica exposta no código-fonte. A chave é salva apenas no `localStorage` do navegador do próprio visitante.

---

## 🚀 Como Hospedar no GitHub Pages

1. **Crie um Repositório:**
   - Crie um novo repositório no [GitHub](https://github.com/new) (ex: `oraculo-zefiro`).
2. **Suba os Arquivos:**
   - Adicione o arquivo da aplicação renomeado obrigatoriamente para **`index.html`** na raiz do repositório.
   - Adicione este **`README.md`**.
3. **Ative o GitHub Pages:**
   - No repositório, clique na aba **Settings** (Configurações).
   - No menu lateral esquerdo, vá em **Pages**.
   - Na seção **Build and deployment > Branch**, selecione a branch `main` (ou `master`) e a pasta `/ (root)`.
   - Clique em **Save**.
4. **Acesse:**
   - Em cerca de 1 a 2 minutos, o site estará no ar na URL:
     ```text
     https://<seu-usuario>.github.io/<nome-do-repositorio>/
     ```

---

## 🔑 Como Conectar a API do Gemini

Ao abrir a página pela primeira vez (ou clicando no ícone de engrenagem ⚙️ no cabeçalho):

1. Gere uma chave gratuita no [Google AI Studio](https://aistudio.google.com/app/apikey).
2. Cole o código da chave no campo indicado.
3. Escolha o modelo desejado (recomendado: `gemini-1.5-flash`).
4. Clique em **Salvar Configurações**. A chave fica armazenada exclusivamente no seu navegador.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação em viewports e modais acessíveis.
- **CSS3 / Glassmorphism:** Tema Crepúsculo Opalino de alta legibilidade, animações 3D de cartas e responsividade móvel.
- **JavaScript (ES6+):** Lógica oracular, manipulação do DOM e requisições assíncronas via `fetch`.
- **Canvas API:** Renderização procedural de poeira estelar de fundo.
- **Web Audio API:** Síntese de osciladores para som de sinos e taças místicas.
- **Marked.js:** Renderização em tempo real de Markdown nas respostas do Oráculo.

---

## 📜 Licença

Este projeto é distribuído sob a licença MIT. Sinta-se livre para clonar, customizar e expandir seus próprios oráculos virtuais!