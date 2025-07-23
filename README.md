# Virtual Piano Simulator

Um piano virtual interativo construído com HTML, CSS e JavaScript puros. Permite reproduzir sons de notas ao clicar nas teclas e usar o teclado físico, além de controla o volume e exibir/ocultar legendas das teclas.

---

## 🎹 Funcionalidades

* **Toque com o mouse:** clique em qualquer tecla para ouvir a nota correspondente.
* **Toque pelo teclado:** use as teclas mapeadas (A, W, S, E, D, F, T, G, Y, H, U, J, K, O, L, P, ;) para tocar as notas.
* **Controle de volume:** ajuste o volume com o slider de volume.
* **Mostrar/ocultar teclas:** marque/desmarque o checkbox para exibir ou ocultar as legendas de nota nas teclas.
* **Animação de toque:** teclas acionadas recebem um efeito visual de destaque.

---

## 🚀 Como executar

1. **Clone este repositório**

   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPO.git
   cd NOME_DO_REPO/piano
   ```

2. **Abra o projeto**

   * Abra `index.html` diretamente no navegador, ou
   * Use uma extensão Live Server no VS Code (`Go Live`).

3. **Interaja com o piano**

   * Clique nas teclas, use o teclado ou ajuste volume e legenda.

---

## 📂 Estrutura de pastas

```
piano/
├── index.html
├── src/
│   ├── script/
│   │   └── engine.js    # Lógica de reprodução e controle de UI
│   ├── styles/
│   │   ├ reset.css      # Reset de estilos
│   │   └ main.css       # Estilo principal
│   └── tunes/           # Arquivos de áudio (.wav) de cada nota
│       ├ a.wav
│       ├ w.wav
│       ├ s.wav
│       └ ...
└── README.md
```

---

## 🔧 Configurações e personalizações

* **Adicionar novas notas:** coloque o arquivo `.wav` em `src/tunes/` e adicione o atributo `data-key` correspondente na tecla em `index.html`.
* **Alterar mapeamento do teclado:** modifique o listener de `keydown` em `engine.js` conforme necessário.
* **Estilizar teclas:** edite `src/styles/main.css` para ajustar cores, sombras e layout.

---

## 📝 Licença

Este projeto está sob a [MIT License](LICENSE).
