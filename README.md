# 🎨 Fundo Mágico

> Transforme suas ideias em backgrounds incríveis com o poder da IA

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)
![AI](https://img.shields.io/badge/AI-Powered-purple.svg)

## 📋 Sobre o Projeto

**Fundo Mágico** é uma aplicação web que utiliza Inteligência Artificial para gerar backgrounds personalizados instantaneamente. Basta descrever o que você imagina e a IA cria o código HTML e CSS pronto para uso!

### ✨ Exemplo de Uso

```
Entrada: "Um gradiente azul suave, que vai do azul claro para o azul escuro"
Saída: Código HTML + CSS completo e funcional
```

## 🚀 Funcionalidades

- 🤖 **Geração por IA**: Descreva o background desejado em linguagem natural
- ⚡ **Código Instantâneo**: Receba HTML e CSS prontos em segundos
- 🎯 **Interface Intuitiva**: Design moderno e fácil de usar
- 📋 **Copy & Paste**: Copie o código gerado com um clique
- 🔄 **N8N Integration**: Workflow automatizado para processamento de requisições

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização e design responsivo
- **JavaScript** - Lógica e interações

### Backend & Automação
- **N8N** - Automação de workflows e integração com IA
- **API de IA** - Geração inteligente de código CSS

### Inteligência Artificial
- Processamento de linguagem natural
- Geração de código automatizada
- Interpretação de descrições visuais


## 🔧 Configuração do N8N

### Workflow Overview

O workflow do N8N processa as requisições da seguinte forma:

```
[Webhook] → [IA Processing] → [Code Generation] → [Response]
```

### Passos para Configurar

1. Importe o workflow em `/workflows/fundo-magico-workflow.json`
2. Configure o nó **Webhook** com a URL pública
3. Configure o nó **AI** com suas credenciais
4. Ative o workflow
5. Teste a conexão usando o endpoint fornecido

## 💻 Como Usar

1. **Acesse a aplicação** no navegador
2. **Digite sua descrição** no campo de texto
   - Exemplo: *"Um gradiente roxo vibrante com partículas brilhantes"*
3. **Clique em "Gerar Background Mágico"**
4. **Visualize o resultado** e copie o código gerado

### Exemplos de Prompts

```
✅ "Um gradiente rosa e laranja estilo pôr do sol"
✅ "Fundo escuro com estrelas cintilantes"
✅ "Gradiente azul oceano com ondas suaves"
✅ "Background minimalista branco com sombras sutis"
```

## 📁 Estrutura do Projeto

```
fundo-magico/
│
├── index.html              # Página principal
├── style.css              # Estilos da aplicação
├── script.js              # Lógica JavaScript
├── assets/                # Imagens e recursos
│   └── background.jpg
├── workflows/             # Workflows N8N
│   └── fundo-magico-workflow.json
├── .env.example           # Exemplo de variáveis de ambiente
├── package.json           # Dependências
└── README.md             # Este arquivo
```

## 🔌 API Integration

### Endpoint Principal

```javascript
POST /generate-background

Body:
{
  "description": "Sua descrição aqui"
}

Response:
{
  "success": true,
  "html": "<div class='magic-bg'>...</div>",
  "css": ".magic-bg { background: linear-gradient(...); }"
}


## 🤝 Contribuindo

Contribuições são bem-vindas! Siga os passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

**Jonas da Silva Dorneles**

- GitHub: [@Jonas-Dev77](https://github.com/Jonas-Dev77/fundo-magico/git)
- LinkedIn: [jonas-dorneles81](https://linkedin.com/in/jonas-dorneles81)
- Email: Jdorneles@hotmail.com

## 🙏 Agradecimentos

- Dev em Dobro pela formação em desenvolvimento web
- Comunidade N8N pelas integrações
- OpenAI/Anthropic pelos modelos de IA

---

⭐ Se este projeto te ajudou, considere dar uma estrela no GitHub!

**Feito com ❤️ e IA**