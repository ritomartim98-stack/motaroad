# Serviços de Mecânica - Website da Oficina de Motociclos

Um website moderno e responsivo para uma oficina de motociclos ("Serviços de Mecânica"), construído com React, TypeScript e Tailwind CSS.

## Funcionalidades

- **Página Inicial** - Visão geral dos serviços, testemunhos e secções de chamada para ação
- **Serviços** - Informação detalhada sobre manutenção, reparações e personalização
- **Loja de Motociclos** - Navegar pelos motociclos disponíveis com especificações detalhadas
- **Detalhes da Motociclo** - Páginas individuais de motociclos com detalhes completos e imagens
- **Catálogo de Peças** - Navegar e adquirir peças e acessórios para motociclos
- **Marcação Online** - Agendar encontros online com um calendário interativo
- **Contacto** - Formulário de contacto e informação de localização

## Tecnologias

- **React 18** - Biblioteca de UI
- **TypeScript** - JavaScript com tipos
- **Vite** - Ferramenta de build e servidor de desenvolvimento
- **Tailwind CSS** - Framework de CSS utilitário
- **shadcn/ui** - Componentes de UI reutilizáveis construídos com Radix UI
- **Framer Motion** - Biblioteca de animações
- **Lucide React** - Biblioteca de ícones
- **React Hook Form** - Gestão de formulários
- **date-fns** - Manipulação de datas

## Começar

### Pré-requisitos

- Node.js 18+
- npm

### Instalação

```bash
npm install
```

### Desenvolvimento

```bash
npm run dev
```

Isto irá iniciar o servidor de desenvolvimento em `http://localhost:5173`.

### Build

```bash
npm run build
```

### Pré-visualizar Build de Produção

```bash
npm run preview
```

## Estrutura do Projeto

```
src/
├── components/
│   ├── ui/           # Componentes de UI reutilizáveis (shadcn/ui)
│   ├── figma/       # Componentes específicos do Figma
│   ├── Header.tsx    # Cabeçalho de navegação principal
│   ├── Footer.tsx    # Rodapé do site
│   ├── ServiceCard.tsx
│   └── BookingDialog.tsx
├── pages/
│   ├── HomePage.tsx
│   ├── ServicesPage.tsx
│   ├── ShopPage.tsx
│   ├── MotorcycleDetailPage.tsx
│   ├── PartsPage.tsx
│   ├── BookingPage.tsx
│   └── ContactPage.tsx
├── styles/
│   └── globals.css
├── App.tsx           # Componente principal da aplicação
├── main.tsx          # Ponto de entrada
└── index.css         # Estilos globais
```

## Design

O design foi originalmente criado no Figma e está disponível em:
https://www.figma.com/design/hfjQb8gZPDTwa0d0IvfRyW/Servi%C3%A7os-de-Mec%C3%A2nica-Site

## Licença

MIT
