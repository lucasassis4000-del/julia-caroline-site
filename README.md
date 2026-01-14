# Site da Dra. Júlia Caroline - Clínica Casulo

Bem-vindo ao repositório do site da Dra. Júlia Caroline, especialista em psicoterapia e atendimento a pacientes idosos. Este projeto contém o site completo com melhorias de SEO, acessibilidade e semântica de código.

## 📋 Descrição do Projeto

O site é uma aplicação web estática (HTML, CSS e JavaScript puro) que apresenta os serviços de psicoterapia oferecidos pela Dra. Júlia Caroline. O site inclui:

- **Página inicial** com apresentação dos serviços
- **Páginas de especialidades** (Psicoterapia, Atendimento a Idosos, etc.)
- **Sistema de agendamento acessível** com integração de calendário
- **Formulário de contato** para novos pacientes
- **Diário emocional** para acompanhamento entre sessões
- **Testes de avaliação** para pacientes

### Melhorias Implementadas

O código foi otimizado com:

- ✅ **SEO**: Meta descriptions, keywords estratégicas, estrutura semântica
- ✅ **Acessibilidade**: ARIA labels, roles semânticos, navegação por teclado
- ✅ **Semântica HTML**: Uso correto de tags `<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`
- ✅ **Performance**: Otimização de imagens e carregamento de recursos
- ✅ **Responsividade**: Design adaptável para mobile, tablet e desktop

## 🚀 Como Rodar Localmente

### Opção 1: Abrir Diretamente no Navegador (Mais Simples)

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/julia-caroline-site.git
cd julia-caroline-site
```

2. Abra o arquivo `index.html` diretamente no navegador:
   - **Windows/Mac/Linux**: Clique duas vezes no arquivo `index.html`
   - Ou arraste o arquivo para a janela do navegador

### Opção 2: Usar um Servidor Estático Local (Recomendado)

Se você tem Node.js instalado, use o `serve` para rodar um servidor local:

#### Passo 1: Instalar dependências
```bash
npm install -g serve
```

#### Passo 2: Iniciar o servidor
```bash
cd julia-caroline-site
serve . --listen 8080
```

#### Passo 3: Acessar no navegador
Abra seu navegador e acesse: **http://localhost:8080**

### Opção 3: Usar Python (Se Tiver Instalado)

Se você tem Python 3 instalado:

```bash
cd julia-caroline-site
python -m http.server 8000
```

Depois acesse: **http://localhost:8000**

## 📁 Estrutura do Projeto

```
julia-caroline-site/
├── index.html                          # Página inicial
├── psicoterapia.html                   # Serviço de psicoterapia
├── idosos.html                         # Atendimento a idosos
├── sobre.html                          # Sobre a Dra. Júlia
├── fale-conosco.html                   # Formulário de contato
├── sistema-agendamento-acessivel.html  # Sistema de agendamento
├── companheiro-vital.html              # Programa de acompanhamento
├── avaliacao.html                      # Testes de avaliação
├── treino-memoria-do-dia.html          # Exercícios de memória
├── teste.html                          # Página de testes
├── index-CzYO3D1A.css                  # Estilos CSS
├── index-B35QfNyO.js                   # Scripts JavaScript
├── relatorio_melhorias.md              # Relatório detalhado de melhorias
├── README.md                           # Este arquivo
└── .gitignore                          # Arquivos ignorados pelo Git
```

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Versão | Descrição |
|-----------|--------|-----------|
| HTML5 | - | Estrutura semântica do site |
| CSS3 | - | Estilos e responsividade |
| JavaScript | ES6+ | Interatividade e funcionalidades |
| Git | - | Controle de versão |
| GitHub | - | Hospedagem do repositório |

## 📝 Comandos Git Essenciais

### Clonar o repositório
```bash
git clone https://github.com/seu-usuario/julia-caroline-site.git
cd julia-caroline-site
```

### Ver o histórico de commits
```bash
git log --oneline
```

### Criar uma nova branch para alterações
```bash
git checkout -b minha-alteracao
```

### Fazer commit de alterações
```bash
git add .
git commit -m "Descrição clara da alteração"
```

### Enviar alterações para GitHub
```bash
git push origin minha-alteracao
```

### Voltar a um commit anterior
```bash
git checkout <hash-do-commit>
```

## 🔗 Links Importantes

- **Repositório GitHub**: https://github.com/seu-usuario/julia-caroline-site
- **Site ao vivo**: (será adicionado quando hospedado)
- **Relatório de melhorias**: Veja `relatorio_melhorias.md`

## 👩‍⚕️ Sobre a Dra. Júlia Caroline

A Dra. Júlia Caroline é uma psicóloga especializada em:
- Psicoterapia individual e em grupo
- Atendimento especializado a pacientes idosos
- Programas de acompanhamento contínuo
- Avaliação e diagnóstico psicológico

Para mais informações, visite o site ou entre em contato através do formulário de contato.

## 📞 Suporte

Se encontrar problemas ao rodar o site localmente:

1. **Verifique se tem Node.js instalado**: `node --version`
2. **Limpe o cache do navegador**: Pressione `Ctrl+Shift+Delete` (ou `Cmd+Shift+Delete` no Mac)
3. **Tente usar uma porta diferente**: `serve . --listen 3000`
4. **Verifique se a porta não está em uso**: `lsof -i :8080` (Mac/Linux)

## 📄 Licença

Este projeto é propriedade da Clínica Casulo. Todos os direitos reservados.

## ✨ Histórico de Versões

| Versão | Data | Alterações |
|--------|------|-----------|
| 1.0.0 | 14/01/2026 | Versão inicial com melhorias de SEO, acessibilidade e semântica |

---

**Desenvolvido com ❤️ para a Dra. Júlia Caroline**
