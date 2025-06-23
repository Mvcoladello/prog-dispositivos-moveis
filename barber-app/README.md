# 🪒 BarberPass MVP

<div align="center">
  <img src="https://via.placeholder.com/200x200/1D2D50/F4C95D?text=✂️" alt="BarberPass Logo" width="120" height="120" style="border-radius: 30px;">
  
  **Plataforma de assinatura corporativa para serviços de beleza**
  
  [![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
  [![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
  [![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
  [![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
</div>

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Modelo de Negócio](#-modelo-de-negócio)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Arquitetura](#-arquitetura)
- [Instalação](#-instalação)
- [Uso](#-uso)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Design System](#-design-system)
- [Roadmap](#-roadmap)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

---

## 🎯 Sobre o Projeto

O **BarberPass** é uma plataforma inovadora que conecta empresas aos melhores serviços de beleza e bem-estar através de um modelo de assinatura corporativa. Nossa solução oferece aos funcionários acesso facilitado a salões, barbearias e clínicas de estética parceiras, enquanto proporciona às empresas um benefício diferenciado e valorizado pelos colaboradores.

### 🌟 Visão
Democratizar o acesso a serviços de beleza e bem-estar no ambiente corporativo, criando uma rede integrada que beneficia empresas, funcionários e estabelecimentos parceiros.

### 🎯 Missão
Simplificar e modernizar a experiência de agendamento de serviços de beleza, oferecendo conveniência, qualidade e economia através de uma plataforma tecnológica robusta e intuitiva.

### 💎 Valores
- **Inovação**: Sempre buscando soluções tecnológicas avançadas
- **Qualidade**: Parceiros rigorosamente selecionados
- **Transparência**: Preços justos e processos claros
- **Conveniência**: Experiência do usuário simplificada
- **Sustentabilidade**: Crescimento responsável e duradouro

---

## 💼 Modelo de Negócio

### 🏢 Para Empresas (B2B)

#### **Planos de Assinatura**
- **Basic**: R$ 25/funcionário/mês - 3 créditos mensais
- **Standard**: R$ 40/funcionário/mês - 5 créditos mensais  
- **Premium**: R$ 60/funcionário/mês - 8 créditos mensais
- **Enterprise**: Personalizado - Volume customizado

#### **Benefícios Corporativos**
- ✅ **Retenção de Talentos**: Benefício diferenciado e valorizado
- ✅ **Bem-estar**: Funcionários mais satisfeitos e produtivos
- ✅ **Gestão Simplificada**: Dashboard administrativo completo
- ✅ **Relatórios**: Analytics detalhados de uso e satisfação
- ✅ **Flexibilidade**: Planos adaptáveis ao tamanho da empresa
- ✅ **ROI Mensurável**: Métricas claras de engajamento

### 👥 Para Funcionários (B2C)

#### **Experiência do Usuário**
- 📱 **App Mobile Intuitivo**: Interface moderna e fácil de usar
- 🔍 **Busca Inteligente**: Filtros por localização, serviço e avaliação
- ⏰ **Agendamento Rápido**: Poucos cliques para marcar horário
- 💳 **Sistema de Créditos**: Sem necessidade de pagamento direto
- ⭐ **Avaliações**: Sistema de feedback para garantir qualidade
- 📍 **Geolocalização**: Encontre estabelecimentos próximos

### 🏪 Para Estabelecimentos Parceiros (B2B)

#### **Programa de Parceria**
- 📈 **Fluxo Garantido**: Clientes pré-pagos e recorrentes
- 💰 **Pagamento Assegurado**: Recebimento garantido via plataforma
- 📊 **Dashboard Parceiro**: Gestão completa de agendamentos
- 🎯 **Marketing Digital**: Exposição na plataforma
- 📱 **Tecnologia Gratuita**: Sistema de gestão sem custo adicional
- 🤝 **Suporte Dedicado**: Equipe especializada para parceiros

---

## ⚡ Funcionalidades

### 📱 **App Mobile (Funcionários)**

#### 🔐 **Autenticação e Perfil**
- Login/cadastro com validação corporativa
- Perfil personalizado com histórico
- Gestão de preferências e notificações
- Integração com dados da empresa

#### 🏠 **Dashboard Personalizado**
- Visão geral de créditos disponíveis
- Próximos agendamentos
- Estabelecimentos recomendados
- Estatísticas pessoais de uso

#### 🔍 **Busca e Descoberta**
- Filtros avançados (localização, serviço, preço, avaliação)
- Mapa interativo com estabelecimentos
- Categorias de serviços organizadas
- Sistema de favoritos

#### 📅 **Agendamento Inteligente**
- Calendário em tempo real
- Seleção de profissionais
- Confirmação automática
- Lembretes push personalizados

#### ✅ **Check-in Digital**
- QR Code para confirmação de presença
- Status em tempo real do atendimento
- Fila de espera virtual
- Notificações de chamada

#### 📊 **Histórico e Avaliações**
- Histórico completo de serviços
- Sistema de avaliação 5 estrelas
- Comentários e feedback
- Estatísticas pessoais

### 🖥️ **Painel Web (Administradores)**

#### 📈 **Dashboard Executivo**
- KPIs em tempo real
- Gráficos de uso e engajamento
- Relatórios financeiros
- Análise de ROI

#### 🏢 **Gestão de Empresas**
- Cadastro e edição de empresas
- Gestão de planos e créditos
- Controle de usuários ativos
- Relatórios por empresa

#### 👥 **Gestão de Usuários**
- Lista completa de funcionários
- Histórico de uso individual
- Gestão de permissões
- Suporte ao usuário

#### 🏪 **Gestão de Parceiros**
- Cadastro de estabelecimentos
- Aprovação e homologação
- Monitoramento de qualidade
- Gestão de comissões

#### 🛠️ **Gestão de Serviços**
- Catálogo completo de serviços
- Precificação e categorização
- Controle de disponibilidade
- Analytics por serviço

### 🏪 **Painel Parceiro (Estabelecimentos)**

#### 📅 **Gestão de Agendamentos**
- Agenda em tempo real
- Confirmação de horários
- Gestão de profissionais
- Controle de capacidade

#### 📊 **Analytics e Relatórios**
- Receita por período
- Clientes mais frequentes
- Serviços mais solicitados
- Avaliações e feedback

#### 💰 **Financeiro**
- Extrato de pagamentos
- Comissões da plataforma
- Relatórios fiscais
- Projeções de receita

---

## 🛠️ Tecnologias

### **Frontend**
- **Next.js 15**: Framework React com App Router
- **TypeScript**: Tipagem estática para maior robustez
- **Tailwind CSS**: Framework CSS utilitário
- **shadcn/ui**: Biblioteca de componentes moderna
- **Lucide React**: Ícones consistentes e elegantes

### **Styling & Design**
- **Design System Apple-inspired**: Bordas arredondadas e animações suaves
- **Responsive Design**: Adaptável a todos os dispositivos
- **Dark Mode**: Suporte completo a tema escuro
- **Animations**: Micro-interações e transições fluidas

### **Fonts & Typography**
- **Inter**: Fonte principal para legibilidade
- **Poppins**: Fonte para títulos e destaques
- **Font Optimization**: Carregamento otimizado via Next.js

### **Development Tools**
- **ESLint**: Linting e qualidade de código
- **Prettier**: Formatação automática
- **Git**: Controle de versão
- **VS Code**: Editor recomendado

---

## 🏗️ Arquitetura

### **Estrutura de Pastas**
\`\`\`
barberpass-mvp/
├── app/                          # Next.js App Router
│   ├── components/              # Componentes da aplicação
│   │   ├── mobile/             # Telas do app mobile
│   │   └── web/                # Telas do painel web
│   ├── fonts.ts                # Configuração de fontes
│   ├── globals.css             # Estilos globais
│   ├── layout.tsx              # Layout principal
│   └── page.tsx                # Página inicial
├── components/                  # Componentes shadcn/ui
│   └── ui/                     # Componentes base
├── public/                     # Arquivos estáticos
├── tailwind.config.ts          # Configuração Tailwind
└── package.json               # Dependências
\`\`\`

### **Padrões de Design**
- **Component-Based**: Arquitetura baseada em componentes reutilizáveis
- **Mobile-First**: Design responsivo priorizando mobile
- **Atomic Design**: Hierarquia clara de componentes
- **Design Tokens**: Cores e espaçamentos padronizados

---

## 🚀 Instalação

### **Pré-requisitos**
- Node.js 18+ 
- npm ou yarn
- Git

### **Passo a Passo**

1. **Clone o repositório**
\`\`\`bash
git clone https://github.com/seu-usuario/barberpass-mvp.git
cd barberpass-mvp
\`\`\`

2. **Instale as dependências**
\`\`\`bash
npm install
# ou
yarn install
\`\`\`

3. **Configure as variáveis de ambiente**
\`\`\`bash
cp .env.example .env.local
# Edite o arquivo .env.local com suas configurações
\`\`\`

4. **Execute o projeto**
\`\`\`bash
npm run dev
# ou
yarn dev
\`\`\`

5. **Acesse a aplicação**
\`\`\`
http://localhost:3000
\`\`\`

### **Scripts Disponíveis**
\`\`\`bash
npm run dev          # Inicia o servidor de desenvolvimento
npm run build        # Gera build de produção
npm run start        # Inicia servidor de produção
npm run lint         # Executa linting
npm run type-check   # Verifica tipos TypeScript
\`\`\`

---

## 📱 Uso

### **Navegação Principal**

1. **Acesse a página inicial** em `http://localhost:3000`
2. **Escolha a plataforma**:
   - 📱 **App Mobile**: Interface para funcionários
   - 🖥️ **Painel Web**: Interface para administradores

### **App Mobile - Fluxo do Usuário**

1. **Login/Cadastro**: Autenticação com dados corporativos
2. **Dashboard**: Visão geral de créditos e agendamentos
3. **Busca**: Encontre estabelecimentos próximos
4. **Agendamento**: Marque seu horário preferido
5. **Check-in**: Confirme presença no estabelecimento
6. **Avaliação**: Avalie o serviço recebido

### **Painel Web - Fluxo Administrativo**

1. **Login Admin**: Acesso com credenciais administrativas
2. **Dashboard**: Métricas e KPIs da plataforma
3. **Gestão**: Empresas, usuários e parceiros
4. **Relatórios**: Analytics e insights de negócio

---

## 🎨 Design System

### **Paleta de Cores**
\`\`\`css
Primary: #1D2D50    /* Azul escuro elegante */
Secondary: #F4C95D  /* Dourado vibrante */
Action: #3D5A80     /* Azul médio para ações */
Success: #4CAF50    /* Verde para sucesso */
Error: #E57373      /* Vermelho suave para erros */
Neutral: #F5F7FA    /* Cinza claro para fundos */
Text Dark: #2E2E2E  /* Texto principal */
Text Secondary: #6E6E6E /* Texto secundário */
\`\`\`

### **Tipografia**
- **Poppins**: Títulos e destaques (300, 400, 500, 600, 700)
- **Inter**: Corpo do texto e interface (300, 400, 500, 600, 700)

### **Espaçamentos**
- **Base**: 4px (0.25rem)
- **Pequeno**: 8px (0.5rem)
- **Médio**: 16px (1rem)
- **Grande**: 24px (1.5rem)
- **Extra Grande**: 32px (2rem)

### **Bordas Arredondadas**
- **Pequeno**: 8px (0.5rem)
- **Médio**: 12px (0.75rem)
- **Grande**: 16px (1rem)
- **Extra Grande**: 20px (1.25rem)
- **Máximo**: 24px (1.5rem)

### **Sombras**
- **Apple**: Sombras sutis inspiradas no design da Apple
- **Apple LG**: Sombras médias para cards importantes
- **Apple XL**: Sombras grandes para modais e overlays

---

## 🗺️ Roadmap

### **Fase 1 - MVP (Atual)**
- ✅ Interface mobile completa
- ✅ Painel administrativo web
- ✅ Design system Apple-inspired
- ✅ Fluxos principais de usuário

### **Fase 2 - Backend & Integração**
- 🔄 API REST completa
- 🔄 Banco de dados PostgreSQL
- 🔄 Autenticação JWT
- 🔄 Sistema de pagamentos
- 🔄 Notificações push

### **Fase 3 - Funcionalidades Avançadas**
- 📋 Sistema de avaliações
- 📋 Chat em tempo real
- 📋 Programa de fidelidade
- 📋 Analytics avançados
- 📋 Integração com calendários

### **Fase 4 - Expansão**
- 📋 App nativo iOS/Android
- 📋 Marketplace de produtos
- 📋 Sistema de vouchers
- 📋 Integração com RH
- 📋 API para terceiros

### **Fase 5 - Escala**
- 📋 Multi-tenancy
- 📋 Internacionalização
- 📋 Machine Learning
- 📋 Blockchain para fidelidade
- 📋 IoT para check-in automático

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Siga estas etapas:

### **Como Contribuir**

1. **Fork o projeto**
2. **Crie uma branch** para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit suas mudanças** (`git commit -m 'Add some AmazingFeature'`)
4. **Push para a branch** (`git push origin feature/AmazingFeature`)
5. **Abra um Pull Request**

### **Padrões de Código**
- Use TypeScript para tipagem
- Siga as convenções do ESLint
- Escreva commits descritivos
- Documente funções complexas
- Teste suas mudanças

### **Reportar Bugs**
- Use as issues do GitHub
- Descreva o problema detalhadamente
- Inclua steps para reproduzir
- Adicione screenshots se necessário

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👥 Equipe

### **Desenvolvimento**
- **Frontend**: React/Next.js specialists
- **Backend**: Node.js/PostgreSQL experts
- **Mobile**: React Native developers
- **DevOps**: AWS/Docker specialists

### **Design**
- **UI/UX**: Design system e experiência do usuário
- **Product**: Estratégia e roadmap do produto
- **Research**: Pesquisa de usuário e mercado

### **Negócios**
- **CEO**: Visão estratégica e liderança
- **CTO**: Arquitetura técnica e inovação
- **CMO**: Marketing e crescimento
- **Sales**: Vendas B2B e parcerias

---

## 📞 Contato

### **Comercial**
- 📧 **Email**: comercial@barberpass.com
- 📱 **WhatsApp**: +55 11 99999-9999
- 🌐 **Website**: www.barberpass.com

### **Suporte Técnico**
- 📧 **Email**: suporte@barberpass.com
- 💬 **Chat**: Disponível no app
- 📚 **Documentação**: docs.barberpass.com

### **Parcerias**
- 📧 **Email**: parcerias@barberpass.com
- 📋 **Formulário**: www.barberpass.com/parceiros
- 📞 **Telefone**: +55 11 3333-3333

---

## 🏆 Reconhecimentos

- **Next.js Team**: Framework incrível
- **Vercel**: Plataforma de deploy
- **Tailwind CSS**: Framework CSS utilitário
- **shadcn**: Biblioteca de componentes
- **Lucide**: Ícones elegantes
- **Apple**: Inspiração para o design system

---

<div align="center">
  <p>Feito com ❤️ pela equipe BarberPass</p>
  <p>© 2024 BarberPass. Todos os direitos reservados.</p>
</div>
