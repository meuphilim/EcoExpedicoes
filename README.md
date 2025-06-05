# 🌿 Bonito Ecoexpedições

## Sobre o Projeto

Site institucional moderno e responsivo para a **Bonito Ecoexpedições**, uma operadora especializada em transporte privativo na região de Bonito, Mato Grosso do Sul. O projeto foi desenvolvido com foco na experiência do usuário, design inspirado na natureza e integração direta com WhatsApp para facilitar o contato com clientes.

## 🚀 Tecnologias Utilizadas

- **React 19.0.0** - Biblioteca principal para construção da interface
- **Tailwind CSS 3.4.17** - Framework CSS para estilização responsiva
- **Framer Motion 12.15.0** - Biblioteca para animações suaves e interativas
- **Lucide React 0.511.0** - Ícones modernos e consistentes
- **React Router DOM 7.5.1** - Roteamento da aplicação
- **Axios 1.8.4** - Cliente HTTP para requisições

## ✨ Funcionalidades

### 🎨 Design e Interface
- **Design Responsivo**: Layout otimizado para desktop, tablet e mobile
- **Tema Natureza**: Paleta de cores inspirada nas águas cristalinas e cerrado de Bonito
- **Animações Suaves**: Transições e animações usando Framer Motion
- **Acessibilidade**: Implementação de práticas de acessibilidade web

### 📱 Seções do Site
- **Header Fixo**: Navegação suave entre seções
- **Hero Section**: Seção principal com call-to-action destacado
- **Sobre Nós**: História, missão e valores da empresa
- **Serviços**: Cards dos principais serviços de transporte
- **Depoimentos**: Avaliações de clientes satisfeitos
- **Contato**: Formulário integrado com WhatsApp
- **Footer**: Informações adicionais e redes sociais

### 🚐 Serviços Oferecidos
1. **Traslado Aeroporto ↔ Bonito**: Transfer seguro entre Campo Grande e Bonito
2. **Transporte para Atrativos**: Deslocamento para pontos turísticos
3. **Motorista Privativo**: Serviço exclusivo durante a estadia
4. **Transfer 24h**: Atendimento noturno e de emergência

### 💬 Integração WhatsApp
- **Botão Flutuante**: Acesso rápido ao WhatsApp em todas as páginas
- **Formulário de Contato**: Envio direto de mensagens via WhatsApp
- **CTAs Estratégicos**: Múltiplos pontos de contato ao longo do site

## 🛠️ Instalação e Execução

### Pré-requisitos
- Node.js (versão 16 ou superior)
- Yarn ou npm

### Passos para execução

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd bonito-ecoexpedicoes
```

2. **Navegue para o diretório frontend**
```bash
cd frontend
```

3. **Instale as dependências**
```bash
yarn install
# ou
npm install
```

4. **Configure as variáveis de ambiente**
```bash
# Copie o arquivo .env.example para .env
cp .env.example .env
```

5. **Execute o projeto**
```bash
yarn start
# ou
npm start
```

6. **Acesse a aplicação**
```
http://localhost:3000
```

## 📁 Estrutura do Projeto

```
frontend/
├── public/                 # Arquivos estáticos
├── src/
│   ├── App.js             # Componente principal
│   ├── App.css            # Estilos globais
│   ├── index.js           # Ponto de entrada
│   └── index.css          # Estilos base
├── package.json           # Dependências do projeto
├── tailwind.config.js     # Configuração do Tailwind
└── postcss.config.js      # Configuração do PostCSS
```

### 🧩 Componentes Principais

- **Header**: Navegação principal com menu responsivo
- **HeroSection**: Seção de destaque com CTA principal
- **AboutSection**: Informações sobre a empresa
- **ServicesSection**: Cards dos serviços oferecidos
- **TestimonialsSection**: Depoimentos de clientes
- **ContactSection**: Formulário de contato e informações
- **Footer**: Rodapé com links e informações adicionais
- **FloatingWhatsApp**: Botão flutuante do WhatsApp
- **SectionWrapper**: Componente reutilizável para seções

## 🎨 Paleta de Cores

- **Emerald Green**: `#10b981` - Cor principal (natureza, confiança)
- **Cyan Blue**: `#00acc1` - Cor secundária (águas cristalinas)
- **Gray Neutral**: `#616161` - Cor de apoio (profissionalismo)
- **White/Light**: Fundos e espaçamentos

## 📞 Informações de Contato

- **WhatsApp**: (67) 99262-4818
- **E-mail**: meuphilim@gmail.com
- **Localização**: Bonito, Mato Grosso do Sul

## 🌐 Deploy

O projeto está configurado para deploy em plataformas como:
- Vercel
- Netlify
- GitHub Pages

### Build para produção
```bash
yarn build
# ou
npm run build
```

## 📝 Scripts Disponíveis

- `yarn start`: Executa o projeto em modo de desenvolvimento
- `yarn build`: Cria a versão otimizada para produção
- `yarn test`: Executa os testes
- `yarn eject`: Remove a abstração do Create React App (irreversível)

## 🔧 Customizações

### Alterando Cores
As cores podem ser customizadas no arquivo `tailwind.config.js`:

```javascript
module.exports = {
  theme: {
    extend: {
      colors: {
        emerald: { /* suas cores */ },
        cyan: { /* suas cores */ }
      }
    }
  }
}
```

### Adicionando Novas Seções
1. Crie o componente da seção
2. Utilize o `SectionWrapper` para consistência
3. Adicione no componente principal `App.js`
4. Atualize a navegação no `Header`

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👥 Desenvolvido por

**Bonito Ecoexpedições** - Transporte privativo especializado em Bonito, MS

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela!**

🌿 **Visite Bonito e conheça as maravilhas naturais do Mato Grosso do Sul!**
