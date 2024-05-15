# Clonando-a-P-gina-do-Youtube-com-CSS

Clonar a página do YouTube é um excelente exercício para praticar suas habilidades de CSS, especialmente o uso de Flexbox para criar layouts responsivos. Vamos dividir este projeto em módulos e descrever cada parte do processo.

### Módulo 1: Estrutura Básica da Página
Primeiro, você precisa criar a estrutura HTML básica da página do YouTube. Isso inclui a `<header>` para a barra de navegação, a `<main>` para o conteúdo principal, e o `<footer>` para o rodapé. Use `<div>` para criar contêineres para diferentes seções, como a lista de vídeos, a barra lateral e o player de vídeo.

### Módulo 2: Estilização com CSS
Depois de ter a estrutura HTML pronta, comece a estilizar com CSS. Defina estilos globais, como fonte, cores e outros elementos visuais que são comuns em toda a página. Use classes e IDs para aplicar estilos específicos a elementos individuais.

### Módulo 3: Flexbox para Layout
O Flexbox é uma ferramenta poderosa para criar layouts flexíveis e responsivos. Use `display: flex;` para definir um contêiner flexível. Utilize propriedades como `flex-direction`, `justify-content`, `align-items` e `flex-wrap` para controlar o layout dos itens dentro dos contêineres flexíveis.

### Módulo 4: Responsividade
Para garantir que sua página clonada seja responsiva e funcione bem em dispositivos de diferentes tamanhos, use media queries para ajustar estilos com base na largura da tela. Por exemplo:

```css
@media (max-width: 768px) {
  .sidebar {
    display: none;
  }

  .video-list {
    flex-direction: column;
  }
}
```

### Módulo 5: Componentes Reutilizáveis
Crie componentes reutilizáveis, como botões, cartões de vídeo e campos de pesquisa. Isso ajudará a manter seu CSS organizado e facilitará a manutenção da página.

### Módulo 6: Detalhes Finais
Adicione os toques finais à sua página, como ícones, sombras e transições para interações do usuário. Esses detalhes podem melhorar significativamente a experiência do usuário.

### Exemplo Prático: Barra de Navegação
Aqui está um exemplo de como você pode estruturar a barra de navegação usando Flexbox:

```html
<header class="navbar">
  <div class="logo">Logo do YouTube</div>
  <div class="search-bar">
    <input type="text" placeholder="Pesquisar">
    <button>Pesquisar</button>
  </div>
  <div class="user-actions">
    <!-- Ícones de ação do usuário -->
  </div>
</header>
```

```css
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

.search-bar input[type="text"] {
  flex-grow: 1;
}

.user-actions {
  display: flex;
}
```

Lembre-se de testar sua página em diferentes navegadores e dispositivos para garantir a compatibilidade e a responsividade.
