# 🥁 BateriaMidi

Projeto desenvolvido como parte do curso da **Alura**, com o objetivo de praticar conceitos fundamentais de **HTML**, **CSS** e **JavaScript**.

---

## 🎯 Visão Geral

**BateriaMidi** é uma aplicação web simples que permite tocar sons de bateria através de cliques nos botões da interface.  
Cada botão corresponde a uma peça da bateria, e ao clicar, o som respectivo é reproduzido.

O projeto foi criado com foco em aprendizado e reforço de manipulação do DOM, eventos e reprodução de áudio no navegador.

---

## 🧩 Estrutura de Pastas

```
/
├── css/
│   └── styles.css
├── images/
├── sounds/
├── index.html
├── main.js
└── README.md
```

### 🗂️ Descrição dos principais arquivos

- **index.html** → Estrutura da interface da bateria (pads e botões).
- **styles.css** → Estilos visuais, layout e responsividade.
- **main.js** → Lógica do projeto, eventos e reprodução dos sons.
- **sounds/** → Pasta contendo os arquivos de áudio.
- **images/** → Imagens e ícones utilizados no projeto.

---

## ⚙️ Funcionamento

1. O usuário acessa a página `index.html`.
2. Cada botão HTML possui um identificador que referencia um som na pasta `sounds/`.
3. O arquivo `main.js` escuta o clique em cada botão e executa o áudio correspondente.
4. É exibido um pequeno feedback visual no botão clicado (opcional).

---

## 🚀 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**

Sem uso de frameworks — o objetivo é fortalecer a base da tríade web.

---

## 💻 Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/ThiagoTorresFerrao/BateriaMidi.git
   ```

2. Acesse o diretório:

   ```bash
   cd BateriaMidi
   ```

3. Abra o arquivo `index.html` em seu navegador preferido.

   > Dica: você pode usar um servidor local simples (`Live Server` no VSCode, ou `python -m http.server`).

4. Clique nos botões para tocar os sons da bateria 🎶

---

## 🌟 Possíveis Melhorias

- Adicionar controle de volume.  
- Permitir tocar com o teclado (atalhos).  
- Criar modo “gravação” para loops.  
- Implementar animações mais elaboradas com CSS ou JS.  
- Adicionar mais instrumentos e sons personalizados.  

---

## 🧠 Conceitos Trabalhados

- Manipulação do DOM.  
- Eventos de clique.  
- Reprodução de áudio com JavaScript.  
- Estruturação e organização de código.  

---

## 📜 Licença

Este projeto foi desenvolvido como parte de um curso da **Alura** e é de livre uso para fins educacionais.

---

👨‍💻 Desenvolvido por [Thiago Torres Ferrão](https://github.com/ThiagoTorresFerrao)
