# WhatsHybrid Lite - Landing Page

## Sobre
Esta é a página principal do WhatsHybrid Lite, uma plataforma avançada de automação e IA para WhatsApp Business.

## Funcionalidades Implementadas

### 1. Hero Section
- Título principal: "Centralize. Atendimento. Automatizado."
- Botão de ação: "Treinar SmartBot"
- Design futurista com gradientes

### 2. Blocos de Contexto IA
- **Sobre o Negócio**: Sincronizado com banco de dados
- **Memória Neural**: Histórico de aprendizados
- **Base de Dados**: Integração com módulos

### 3. Seção de Robôs
- Dois robôs SVG animados
- Seletor de perfis (Dono, Gerente, Vendedor, Suporte)
- Botão "Conectar WhatsApp" que abre web.whatsapp.com
- Mockup de celular com chat simulado
- Campo para assunto da conversa
- Botão "Iniciar Conversa Entre Robôs"

### 4. Features Section
- 3 cards com efeito tilt 3D:
  - Neural AI Response
  - CRM Híbrido Visual
  - Automação Infinita

### 5. Painel de Envio via WhatsApp
- Lista de números (textarea)
- Campo de mensagem com botão para adicionar mídia
- Configurações: intervalo, canal (DOM/API), modelo IA, modo de envio
- Botão "Gerar Links"
- Prévia dos links gerados
- Prévia de envio com estatísticas
- Status dos envios em tempo real

### 6. Pricing Section
- Toggle mensal/anual (20% desconto anual)
- 3 Planos:
  - **Starter**: R$ 97/mês
  - **Hybrid Pro**: R$ 297/mês (destaque)
  - **Agency**: R$ 997/mês

### 7. Modal de Login
- Campos de email e senha
- Botão "Conectar com Google"
- Link para criar conta

### 8. Painel de Treinamento IA (Modal Completo)
7 abas funcionais:
- **Negócio**: Informações da empresa, políticas
- **Catálogo**: Adicionar produtos manualmente ou importar CSV
- **FAQ**: Perguntas e respostas
- **Respostas Rápidas**: Gatilhos e respostas automáticas
- **Documentos**: Upload de PDF, TXT, MD
- **Tom de Voz**: Estilo, emojis, saudação, despedida
- **Testar IA**: Chat de teste com métricas de treinamento

## Tecnologias Utilizadas
- **Tailwind CSS**: Framework CSS via CDN
- **AOS.js**: Biblioteca de animações on scroll
- **Lucide Icons**: Ícones modernos
- **Canvas API**: Partículas neurais animadas
- **JavaScript Vanilla**: Interatividade

## Efeitos Visuais
- ✨ Glassmorphism em cards e modais
- 🎨 Gradientes roxo/rosa no tema
- 🖱️ Cursor customizado (círculo roxo)
- 🌊 Animação de ondas na seção de robôs
- 🤖 Robôs com animação float
- 🧠 Partículas neurais conectadas no background
- 💫 Efeito tilt 3D nos cards

## Integração com Backend
O código inclui placeholders para integração com o backend PHP existente:
- Funções `saveBusinessInfo()`, `saveProduct()`, etc.
- Comentários TODO indicando pontos de integração
- Preparado para sincronização com banco de dados (tabela ai_knowledge)

## Como Usar

### Desenvolvimento Local
1. Abra `index.html` diretamente no navegador, ou
2. Use um servidor HTTP local:
   ```bash
   python3 -m http.server 8080
   ```
3. Acesse: `http://localhost:8080/index.html`

### Produção
- Faça upload do arquivo para o servidor web
- As dependências são carregadas via CDN (requer conexão com internet)

## Observações Importantes

### CDN Dependencies
O arquivo utiliza CDNs para:
- Tailwind CSS
- AOS.js
- Lucide Icons
- Google Fonts (Inter)

**Nota**: Em ambientes com bloqueio de CDNs externos, considere fazer download local dos recursos.

### Compatibilidade
- ✅ Chrome/Edge (recomendado)
- ✅ Firefox
- ✅ Safari
- ⚠️ Mobile (responsivo, mas melhor em desktop)

### Próximos Passos
1. Integrar com backend PHP existente
2. Implementar autenticação real
3. Conectar com banco de dados MySQL
4. Adicionar validação de formulários
5. Implementar upload de arquivos real
6. Integrar com API do WhatsApp

## Estrutura do Código
- **Linhas 1-271**: HTML Head + Estilos CSS
- **Linhas 272-646**: Hero, Context Blocks, Robots Section
- **Linhas 647-749**: Features + WhatsApp Sending Panel
- **Linhas 750-865**: Pricing + Footer
- **Linhas 866-955**: Modal de Login
- **Linhas 956-1020**: Painel de Treinamento IA (abas)
- **Linhas 1021-1380**: JavaScript (interatividade)

## Suporte
Para dúvidas ou problemas, consulte a documentação do projeto principal.
