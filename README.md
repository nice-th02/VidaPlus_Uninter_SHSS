# 🏥 VidaPlus - Sistema de Gestão Hospitalar

![VidaPlus Logo](https://img.shields.io/badge/VidaPlus-Healthcare%20System-06b6d4?style=for-the-badge&logo=hospital&logoColor=white)

Um sistema completo de gestão hospitalar desenvolvido com HTML5, CSS3 e JavaScript, oferecendo interfaces modernas e responsivas para diferentes perfis de usuário no ambiente médico.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação e Uso](#instalação-e-uso)
- [Perfis de Usuário](#perfis-de-usuário)
- [Recursos Responsivos](#recursos-responsivos)
- [Screenshots](#screenshots)
- [Contribuição](#contribuição)
- [Licença](#licença)

## 🎯 Sobre o Projeto

O **VidaPlus** é um sistema de gestão hospitalar moderno que oferece interfaces intuitivas e funcionais para diferentes perfis de usuários no ambiente médico. Desenvolvido com foco na experiência do usuário e responsividade, o sistema proporciona uma solução completa para gestão de consultas, pacientes, médicos e administração hospitalar.

### 🎨 Design Philosophy

- **Moderno e Limpo**: Interface minimalista com foco na usabilidade
- **Responsivo**: Adaptável a todos os dispositivos e tamanhos de tela
- **Acessível**: Cores e contrastes otimizados para melhor legibilidade
- **Intuitivo**: Navegação clara e fluxos de trabalho lógicos

## ✨ Funcionalidades

### 🔐 Sistema de Autenticação
- **Login** com validação de credenciais
- **Cadastro** de novos usuários
- **Recuperação de senha** com interface intuitiva
- **Logout** seguro com confirmação

### 👨‍⚕️ Dashboard Médico
- **Agenda de consultas** com visualização clara
- **Gestão de pacientes** com histórico completo
- **Controle de exames** e resultados
- **Sistema de teleconsultas** integrado
- **Estatísticas** em tempo real

### 👤 Dashboard do Paciente
- **Informações pessoais** e médicas centralizadas
- **Histórico de consultas** e exames
- **Gestão de medicamentos** com lembretes
- **Agendamento** de consultas e exames
- **Notificações** personalizadas

### 🛠️ Dashboard Administrativo
- **Visão geral** do sistema hospitalar
- **Gestão de usuários** e permissões
- **Relatórios** e estatísticas gerais
- **Configurações** do sistema
- **Monitoramento** de atividades

### 📱 Recursos Avançados
- **Modais interativos** com informações detalhadas
- **Sistema de notificações** em tempo real
- **Tema claro/escuro** (preparado para implementação)
- **Breadcrumbs** para navegação
- **Tooltips** informativos
- **Animações** suaves e profissionais

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização moderna com Flexbox e Grid
- **JavaScript (ES6+)** - Interatividade e funcionalidades dinâmicas
- **Font Awesome 6.4.0** - Ícones profissionais
- **Google Fonts** - Tipografia moderna (Poppins, JetBrains Mono)

### Design System
- **CSS Variables** - Sistema de cores consistente
- **Media Queries** - Design responsivo completo
- **Backdrop Filter** - Efeitos de vidro modernos
- **CSS Grid & Flexbox** - Layouts flexíveis
- **CSS Animations** - Transições suaves

### Responsividade
- **Mobile First** - Design otimizado para dispositivos móveis
- **Breakpoints** - 1200px, 1024px, 768px, 480px
- **Touch Friendly** - Elementos otimizados para touch
- **Progressive Enhancement** - Funcionalidades que se adaptam

## 📁 Estrutura do Projeto

```
VidaPlus/
├── 📄 index.html              # Página inicial
├── 🔐 login.html              # Sistema de login
├── 📝 cadastro.html           # Cadastro de usuários
├── 🔄 recuperacao.html        # Recuperação de senha
├── 👨‍⚕️ medico.html              # Dashboard do médico
├── 👤 paciente.html           # Dashboard do paciente
├── 🛠️ admin.html              # Dashboard administrativo
├── 📊 painel-admin.html       # Painel administrativo
├── 👤 painel-paciente.html    # Painel do paciente
├── 👨‍⚕️ painel-profissional.html # Painel do profissional
├── 📁 css/
│   └── base.css              # Estilos base
└── 📄 README.md              # Documentação do projeto
```

## 🚀 Instalação e Uso

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desenvolvimento)


### Uso Básico

1. **Acesse a página inicial** (`index.html`)
2. **Faça login** ou **cadastre-se** usando `login.html` ou `cadastro.html`
3. **Navegue** entre os diferentes dashboards conforme seu perfil
4. **Explore** as funcionalidades específicas de cada área

## 👥 Perfis de Usuário

### 👨‍⚕️ Médico
- **Acesso**: `medico.html`
- **Funcionalidades**:
  - Visualizar agenda de consultas
  - Gerenciar pacientes
  - Controlar exames e resultados
  - Realizar teleconsultas
  - Acompanhar estatísticas

### 👤 Paciente
- **Acesso**: `paciente.html`
- **Funcionalidades**:
  - Visualizar informações pessoais
  - Consultar histórico médico
  - Gerenciar medicamentos
  - Agendar consultas e exames
  - Receber notificações

### 🛠️ Administrador
- **Acesso**: `admin.html`
- **Funcionalidades**:
  - Visão geral do sistema
  - Gestão de usuários
  - Relatórios e estatísticas
  - Configurações do sistema
  - Monitoramento de atividades

## 📱 Recursos Responsivos

### Breakpoints Implementados
- **1200px+**: Desktop completo
- **1024px-1199px**: Tablets grandes
- **768px-1023px**: Tablets e mobile grande
- **480px-767px**: Smartphones
- **<480px**: Smartphones pequenos

### Adaptações por Dispositivo
- **Desktop**: Layout completo com sidebar fixa
- **Tablet**: Sidebar oculta com toggle mobile
- **Mobile**: Layout vertical otimizado
- **Touch**: Elementos otimizados para toque


## 🎨 Design System

### Paleta de Cores
- **Primary**: #06b6d4 (Cyan)
- **Secondary**: #0891b2 (Cyan escuro)
- **Accent**: #0e7490 (Cyan mais escuro)
- **Success**: #10b981 (Verde)
- **Warning**: #f59e0b (Amarelo)
- **Error**: #ef4444 (Vermelho)
- **Admin**: #dc2626 (Vermelho bordo)

### Tipografia
- **Fonte Principal**: Poppins (300-800)
- **Fonte Monospace**: JetBrains Mono (400-600)
- **Tamanhos**: Escala responsiva de 0.7rem a 2.5rem

### Componentes
- **Cards**: Bordas arredondadas, sombras suaves
- **Botões**: Gradientes, hover effects
- **Modais**: Backdrop blur, animações
- **Sidebar**: Glass morphism, navegação intuitiva

## 🔧 Personalização

### Cores
As cores podem ser facilmente alteradas modificando as variáveis CSS no início de cada arquivo:

```css
:root {
    --primary-color: #06b6d4;
    --secondary-color: #0891b2;
    --accent-color: #0e7490;
    /* ... outras cores */
}
```

### Layout
- **Sidebar**: Largura ajustável via CSS
- **Grids**: Colunas configuráveis
- **Breakpoints**: Personalizáveis conforme necessário

## 🚀 Próximos Passos

### Funcionalidades Futuras
- [ ] **Backend Integration** - Conectar com API real
- [ ] **Autenticação JWT** - Sistema de login seguro
- [ ] **Base de Dados** - Persistência de dados
- [ ] **Notificações Push** - Alertas em tempo real
- [ ] **Relatórios PDF** - Exportação de dados
- [ ] **Tema Escuro** - Modo noturno completo
- [ ] **PWA** - Aplicativo instalável
- [ ] **Testes** - Cobertura de testes automatizados

### Melhorias Planejadas
- [ ] **Performance** - Otimização de carregamento
- [ ] **Acessibilidade** - WCAG 2.1 AA
- [ ] **Internacionalização** - Múltiplos idiomas
- [ ] **Offline Support** - Funcionamento offline
- [ ] **Analytics** - Métricas de uso

## 🤝 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. **Fork** o projeto
2. **Crie** uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. **Commit** suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. **Push** para a branch (`git push origin feature/AmazingFeature`)
5. **Abra** um Pull Request

### Padrões de Código
- **HTML**: Semântico e acessível
- **CSS**: BEM methodology, variáveis CSS
- **JavaScript**: ES6+, funções puras
- **Comentários**: Código autoexplicativo

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
