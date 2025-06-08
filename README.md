# O Cálculo no Coração da Computação

Uma exploração interativa de como as integrais e derivadas impulsionam a tecnologia que usamos todos os dias.

![image](https://github.com/user-attachments/assets/f672b32f-9c41-4610-8bb1-4936469074f5)

## 🚀 Acesso ao Site

Acesse a aplicação online: [https://seu-usuario.github.io/seu-repositorio](https://seu-usuario.github.io/seu-repositorio)

> **Nota:** Substitua `seu-usuario` e `seu-repositorio` pelos seus dados reais do GitHub.

## 📋 Sobre o Projeto

Este projeto oferece uma experiência interativa para entender como conceitos fundamentais do cálculo diferencial e integral são aplicados na ciência da computação moderna. A aplicação inclui:

## 🎯 Recursos Principais

- **Design Apple-Inspirado**: Interface limpa e elegante com estética minimalista
- **Exploração Interativa**: Cards expansíveis com animações suaves e transições refinadas
- **Visualizações Dinâmicas**: Gráficos interativos usando Chart.js com paleta de cores Apple
- **Artigo Completo**: Versão textual aprofundada com tipografia otimizada
- **Design Responsivo**: Experiência consistente em desktop e mobile
- **Tema Consistente**: Design system unificado inspirado nas diretrizes da Apple

### 🧮 Temas Abordados

#### Aplicações de Integrais

- **Processamento de Sinais e Imagens**: Filtragem, Transformadas de Fourier, Convolução
- **Probabilidade e IA**: PDFs, Valor Esperado, Tomada de Decisão
- **Computação Gráfica**: Ray Tracing, Renderização, Simulações

#### Aplicações de Derivadas

- **Inteligência Artificial**: Descida do Gradiente, Backpropagation, Otimização
- **Robótica**: Controladores PID, Sistemas de Controle
- **Animação e Física**: Simulação de Movimento, Detecção de Bordas

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica moderna
- **CSS3**: Sistema de design Apple-inspirado com variáveis CSS customizadas
- **Chart.js**: Visualizações interativas com paleta de cores Apple
- **JavaScript Vanilla**: Interatividade fluida e animações suaves
- **Apple Design System**: Paleta de cores, tipografia e componentes inspirados na Apple
- **GitHub Pages**: Hospedagem estática e deploy automatizado

## 📱 Como Usar

1. **Navegação Principal**: Escolha entre "Aplicações de Integrais" ou "Aplicações de Derivadas"
2. **Exploração de Temas**: Clique nos cards para expandir com animações suaves
3. **Interação Visual**: Use controles intuitivos nos gráficos (botões, sliders) com feedback Apple-style
4. **Artigo Completo**: Acesse a versão textual completa com tipografia otimizada para leitura
5. **Experiência Responsiva**: Interface adaptável que mantém a elegância em qualquer dispositivo

## ✨ Características do Design

### Elementos Visuais Apple

- **Backdrop Blur**: Efeitos de desfoque translúcido nos cards
- **Sombras Sutis**: Sistema de elevação com sombras progressivas
- **Animações Fluidas**: Transições suaves com curvas de Bézier otimizadas
- **Estados Hover**: Feedback visual refinado em todos os elementos interativos
- **Sistema de Grid**: Layout responsivo que mantém proporções harmoniosas

### Experiência do Usuário

- **Hierarquia Visual**: Tipografia e espaçamento que guiam naturalmente o olhar
- **Interações Intuitivas**: Elementos respondem de forma previsível e agradável
- **Consistência**: Mesmo padrão visual entre página principal e artigo
- **Acessibilidade**: Contraste otimizado e elementos focáveis claramente definidos

## 🚀 Configuração do GitHub Pages

### Passo 1: Configurar o Repositório

1. Faça push do código para seu repositório no GitHub
2. Vá em **Settings** > **Pages**
3. Em **Source**, selecione **Deploy from a branch**
4. Escolha a branch **main** e pasta **/ (root)**
5. Clique em **Save**

### Passo 2: Personalizar a Configuração

Edite o arquivo `_config.yml` e substitua:

- `USERNAME` pelo seu nome de usuário do GitHub
- `REPOSITORY_NAME` pelo nome do seu repositório
- `Seu Nome` pelo seu nome real

### Passo 3: Verificar o Deploy

- O site ficará disponível em `https://seu-usuario.github.io/seu-repositorio`
- O deploy pode levar alguns minutos
- Verifique a aba **Actions** para acompanhar o processo

## 🎨 Design e Tema

### Sistema de Cores Apple

O projeto utiliza a paleta oficial da Apple para uma experiência visual refinada:

- **Cores Primárias**: `#ffffff` (branco), `#f5f5f7` (cinza claro)
- **Texto**: `#1d1d1f` (escuro), `#86868b` (secundário)
- **Acentos**: `#007aff` (azul Apple), `#34c759` (verde), `#ff3b30` (vermelho)
- **Componentes**: Bordas arredondadas, sombras sutis, backdrop blur

### Tipografia

- **Font Stack**: `-apple-system, BlinkMacSystemFont, "SF Pro Display", "Segoe UI", Roboto, sans-serif`
- **Características**: Anti-aliasing otimizado, letter-spacing refinado, hierarquia clara

## 🎨 Personalização

### Cores e Tema

O projeto utiliza um sistema de variáveis CSS inspirado no design da Apple:

```css
:root {
  --apple-bg: #ffffff;
  --apple-secondary-bg: #f5f5f7;
  --apple-text: #1d1d1f;
  --apple-accent: #007aff;
  /* ... outras variáveis */
}
```

Para personalizar, modifique as variáveis CSS no arquivo `index.html` e `artigo.html`.

### Conteúdo e Funcionalidades

- **Textos**: Edite os objetos `contentData` no JavaScript de `index.html`
- **Gráficos**: Modifique as funções de criação de gráficos (ex: `createOptimizationChart()`)
- **Artigo**: Edite diretamente o conteúdo HTML em `artigo.html`
- **Cores dos Gráficos**: Atualize as paletas nos objetos Chart.js para manter consistência

### Componentes Estilizados

- **Cards**: `border-radius: 20px`, `backdrop-filter: blur(20px)`
- **Botões**: `border-radius: 12px`, transições suaves com `cubic-bezier`
- **Navegação**: Estilo pill com estados hover refinados

## 🔄 Histórico de Design

### Versão 2.0 - Tema Apple (Atual)

- **Visual**: Design limpo e minimalista inspirado na Apple
- **Cores**: Paleta de branco, cinza claro e azul Apple (#007aff)
- **Tipografia**: Sistema de fontes da Apple com anti-aliasing otimizado
- **Componentes**: Cards com backdrop blur, botões refinados, animações suaves

### Versão 1.0 - Tema Hacker (Anterior)

- **Visual**: Estética terminal com fundo escuro
- **Cores**: Verde neon (#00ff41) sobre fundo preto
- **Tipografia**: Fontes monospace (Monaco, Hack)
- **Efeitos**: Animações de scanning, glow effects, estilo matrix

A migração manteve 100% da funcionalidade enquanto transformou completamente a experiência visual.

## 🤝 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença GNU. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Para dúvidas, sugestões ou feedback, abra uma issue no repositório.

---

**Desenvolvido com 🤍 para democratizar o conhecimento matemático na era digital.**
_Design inspirado na elegância e simplicidade da Apple._
