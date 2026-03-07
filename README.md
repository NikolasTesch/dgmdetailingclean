# 🛋️ DGM Detailing Clean - Landing Page

Uma Landing Page de altíssima conversão desenvolvida para um negócio local especializado em **Limpeza e Higienização de Estofados e Detailing Automotivo**, com atuação em Itinga-MG e região.

O objetivo principal desta página é a captação de leads qualificados, destacando a qualidade premium do serviço e direcionando o cliente diretamente para um atendimento personalizado via WhatsApp.

---

## 🚀 Funcionalidades

- **Design Responsivo (Mobile-First):** Layout moderno e perfeitamente adaptável para todos os tamanhos de tela (celulares, tablets e desktops).
- **SEO Local Avançado:** Código construído focado 100% no Google. Contém Meta Tags essenciais, tags Open Graph para compartilhamento rico nas redes e a marcação estruturada do Schema.org (`LocalBusiness`) indicando a localização em Itinga-MG.
- **Alta Performance:** HTML limpo e otimizado com foco na nota máxima em relatórios de performance como o Google Lighthouse.
- **Animações Fluidas:** Experiência *premium* do usuário com efeitos de surgimento de tela suaves (*Scroll Reveal*) gerenciados modernamente através do *Intersection Observer* em JS.
- **Componentes Interativos:**
    - Menu lateral (Mobile Menu) animado e prático.
    - Perguntas Frequentes (FAQ) em formato de Acordeão expansível.
    - Tabela de serviços e cards interativos com efeitos de *hover*.
    - Botões CTA (Call-to-Action) com efeitos estéticos e redirecionamento direto (com mensagem pré-definida) para o WhatsApp.
- **Acessibilidade:** Elementos com atributos `aria-label` e textos alternativos em imagens para suportar leitores de tela de forma nativa.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

O projeto foi inteiramente construído "Vanilla" (Puro), sem dependência de bibliotecas pesadas de UI (como Bootstrap) ou frameworks (como React/Next), visando a velocidade máxima de carregamento.

- **HTML5 Semântico:** Uso correto de tags como `<header>`, `<main>`, `<section>`, `<footer>` e `<nav>`.
- **CSS3 Moderno:** Utilização intensiva de `Flexbox` e `CSS Grid`. Sistema de cores via Variáveis no `:root` (Branco gelo e tons vibrantes e profundos de Azul).
- **JavaScript Vanilla (ES6+):** Código limpo focado na manipulação do DOM e interceptação de eventos de scroll (revelar seções) e cliques.
- **Ícones Externos:** [Phosphor Icons](https://phosphoricons.com/) para todos os pictogramas da interface (elegantes e finos).
- **Tipografia:** Google Fonts — *Inter* para excelente legibilidade de corpo de texto, e *Outfit* para os títulos impactantes.

---

## 📂 Estrutura de Arquivos

```text
/dgmdetailingclean
│
├── index.html       # Estrutura principal da página, meta tags e conteúdo.
├── style.css        # Camada de estilos estéticos, utilitários de grid e media queries.
├── script.js        # Lógica de interatividade (Menu Mobile, FAQ, Animações).
└── README.md        # Esta documentação do projeto.
```

---

## ⚙️ Como Executar o Projeto

Como a página é **100% estática**, você não precisa configurar ambiente de desenvolvimento (Node.js, build tools, etc.) para visualizá-la.

1. **Clone ou baixe o diretório** em sua máquina.
2. Dê um **duplo clique no arquivo `index.html`** para abrí-lo diretamente no seu navegador padrão (Chrome, Firefox, Safari, Edge).
3. **Dica para edição:** Para ver alterações em tempo real após editar o código, utilize extensões como o "Live Server" no VSCode.
4. **Para testar o modo celular no PC:** Abra a página no navegador, pressione `F12` para abrir o DevTools e clique no ícone que simula Mobile/Dispositivos (ou atalho `Ctrl+Shift+M`).