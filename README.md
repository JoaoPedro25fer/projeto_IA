# 🎯 Classificador de Imagem - Teachable Machine

Um projeto web responsivo para classificação de imagens em tempo real utilizando **Teachable Machine** do Google com interface moderna e intuitiva.

## ✨ Características

- **Interface Responsiva**: Design adaptável para desktop, tablet e mobile
- **Bootstrap 5**: Estilização moderna e profissional
- **Barras de Progresso**: Visualização clara do nível de confiança para cada classe
- **Câmera em Tempo Real**: Classificação contínua através da webcam
- **Pronto para Deploy**: Compatível com GitHub Pages

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos customizados e responsivos
- **Bootstrap 5** - Framework CSS para design responsivo
- **TensorFlow.js** - Machine learning no navegador
- **Teachable Machine** - Modelo de classificação pré-treinado
- **JavaScript** - Lógica de interação

## 📋 Requisitos

- Navegador moderno com suporte a:
  - Câmera/Webcam
  - WebGL (para TensorFlow.js)
  - ES6 JavaScript

## 🎮 Como Usar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/JoaoPedro25fer/projeto_IA.git
   cd projeto_IA
   ```

2. **Abra o arquivo HTML**
   - Abra `index.html` em um navegador moderno
   - Ou acesse através do GitHub Pages

3. **Use a aplicação**
   - Clique no botão "Iniciar câmera"
   - Permita o acesso à sua webcam
   - Aponte a câmera para os objetos que deseja classificar
   - Veja as previsões atualizarem em tempo real com barras de progresso

## 📁 Estrutura do Projeto

```
projeto_IA/
├── index.html                    # Arquivo principal da aplicação
├── reconhecimento_imagem/        # Subdiretório com recursos adicionais
└── README.md                     # Este arquivo
```

## 🎨 Componentes da Interface

- **Header**: Título e descrição do projeto
- **Painel de Controle**: Botão para iniciar a câmera e preview da webcam
- **Painel de Resultados**: Exibição das classes com:
  - Nome da classe
  - Porcentagem de confiança
  - Barra de progresso visual
  - Input range (range slider)

## ⚙️ Configuração do Modelo

Para usar seu próprio modelo Teachable Machine:

1. Acesse [Teachable Machine](https://teachablemachine.withgoogle.com/)
2. Treine um modelo de classificação de imagem
3. Exporte o modelo e copie a URL
4. Substitua a constante `URL` no script:
   ```javascript
   const URL = "SEU_URL_AQUI/";
   ```

## 🌐 Deploy no GitHub Pages

1. Ative GitHub Pages no repositório
2. Selecione a branch `main` como fonte
3. Acesse `https://JoaoPedro25fer.github.io/projeto_IA/`

## 🔧 Personalizações Possíveis

- Alterar cores do gradiente de fundo em `body { background: linear-gradient(...) }`
- Modificar tamanho da câmera: `new tmImage.Webcam(320, 320, flip)`
- Ajustar cores das barras de progresso e badges
- Adicionar mais seções ou informações

## 📱 Responsividade

O projeto é totalmente responsivo com breakpoints Bootstrap:
- **Mobile**: < 768px
- **Tablet**: 768px - 1199px
- **Desktop**: ≥ 1200px

## 📝 Licença

Este projeto utiliza bibliotecas de código aberto:
- [TensorFlow.js](https://www.tensorflow.org/js) - Apache 2.0
- [Teachable Machine](https://teachablemachine.withgoogle.com/) - Google
- [Bootstrap](https://getbootstrap.com/) - MIT

## 👨‍💻 Autor

**João Pedro Fernandes**

## 🤝 Contribuições

Sinta-se livre para fazer fork, abrir issues e enviar pull requests!

## ❓ Suporte

Para mais informações sobre Teachable Machine, acesse:
- [Documentação Oficial](https://teachablemachine.withgoogle.com/faq)
- [TensorFlow.js Docs](https://js.tensorflow.org/)

---

**Desenvolvido com ❤️ para GitHub Pages**
