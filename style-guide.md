## Design System — Projeto Cyberpunk

## 🎯 Objetivo da Atividade
Construir uma página web utilizando **HTML e CSS**, seguindo um padrão visual definido.

---
## 🎨 Conceito Visual

Este projeto segue a estética **cyberpunk**, caracterizada por:
- Alto contraste
- Cores neon sobre fundo escuro
- Tipografia futurista
- Conteúdo centralizado

---

## Estrutura do Projeto

A atividade já possui:
- Pasta de imagens
- Pasta de CSS
- Pasta de fontes
- Arquivo  styles.css 
- Não apagar as primeiras linhas da CSS
**Não excluir ou renomear arquivos/pastas**

---

##  Estrutura da Página (HTML)

A página deve conter:

1. **Título principal**
2. **Subtítulo secundário**
3. **Parágrafo de texto**
4. **Imagem principal (cyber.png)**
5. **Link externo - https://www.cyberpunk.net**
6. **Galeria com 3 imagens - cyber-1.jpg - cyber-2.jpg - cyber-3.jpg**

---

## FORMATAÇÕES

---

## Montar RESET CSS (OBRIGATÓRIO)

---

## Variáveis CSS (OBRIGATÓRIO)


### Paleta de Cores
| Variável           | Valor     |
|--------------------|-----------|
| --color-yellow     | #F9F002 |
| --color-blue       | #4ABED5 |
| --color-dark       | #111111 |
| --color-white      | #FFFFFF |

---

### Espaçamentos
| Variável           | Valor  |
|--------------------|--------|
| --spacing-md       | 20px   |
| --spacing-lg       | 50px   |
| --spacing-xl       | 180px  |

---

### Tipografia
| Variável                  | Valor  |
|---------------------------|--------|
|  --font-size-title        | 150px  |
|  --font-size-subtitle     | 50px   |
|  --font-size-text         | 25px   |

---

##  Componentes e Formatação

### Corpo da página
- Cor de fundo: --color-dark
- Fonte: rajdhani

---

### Título Principal
- Fonte: cyberpunk
- Cor do texto: --color-yellow
- Tamanho da fonte:  --font-size-title 
- Alinhamento texto: centralizado
- Margem superior:  --spacing-md 
- Espaçamento letras: 4px

---

## Subtítulo 
- Alinhamento texto: centralizado
- Margem inferior:  --spacing-md 
- Cor do texto:  --color-blue 
- Tamanho da fonte:  --font-size-subtitle 

---

### 📝 Texto
- Cor do texto:  --color-yellow 
- Tamanho:  --font-size-text 
- Peso da fonte: 700
- Margem:  --spacing-md 
- Alinhamento texto: centralizado

---

### Div para imagem banner 
- Alinhamento da imagem: centralizado
- Margem externa:  --spacing-md 

---

### div para imagem
- Alinhamento: centralizado

---

### Imagem banner - Coloque na div
- Borda tamanho: 5px
- Borda estilo:  sólida 
- Borda cor: --color-white (5px)

---

### div para link
- Alinhamento texto: centralizado
- Margem superior e inferior: --spacing-lg

---

### Link - Coloque na div
- Fundo:  --color-blue 
- Texto: --color-white
- Tamanho da fonte: --font-size-text 
- Padding:
  - Vertical:  --spacing-md
  - Horizontal:  --spacing-xl 
- Decoração do texto: Sem
- Peso da fonte: 900
- Borda tamanho: 5px
- Borda estilo:  sólida 
- Borda cor: --color-white (5px)
- Transição para hover: 0.5s

---

#### Hover do link (obrigatório)
- Fundo:  --color-yellow 
- Texto:  --color-dark 

---

### div para as três imagens
- Margem externa:  --spacing-md 
- Alinhamento: centralizado

---

### Imagens devem ficar dentro da div
- Margem externa:  --spacing-md 
- 3 imagens centralizadas
- Borda tamanho: 5px
- Borda estilo:  sólida 
- Borda cor: --color-yellow
- USAR: filter: grayscale(1) 
- Transição para hover: 0.5s 

---

#### Hover das imagens (obrigatório)
- Tamanho da imagem aumenta 10% com hover
- USAR: filter: grayscale(0)

---

## 🎛️ Interações

| Elemento | Comportamento |
|----------|--------------|
| Botão    | Muda cor no hover |
| Imagens  | Remove grayscale + aumenta |

---

##  Regras IMPORTANTES

- Usar variáveis CSS obrigatoriamente  
- Não usar valores diretos (ex:  20px ,  #fff )  
- Centralizar conteúdo  
- Seguir estrutura proposta  
- Aplicar efeitos de hover  

---

## Erros que NÃO podem acontecer

- Não usar variáveis
- Usar valores fixos no CSS
- Não aplicar hover
- Não centralizar elementos
- Estrutura HTML incompleta

---

##  Avaliação

| Critério               | Pontos |
|------------------------|--------|
| Uso de variáveis       | 2      |
| Estrutura HTML         | 2      |
| Fidelidade ao design   | 2      |
| Interações (hover)     | 2      |
| Organização do código  | 2      |

**Total: 10 pontos**

**Entrega**
## Entegar arquivo compactado
## Enviar pelo portal da Fiap - área de entrega de trabalhos 
## Fazer a entrega até 05/10
## Se fizer em dupla colocar nome completo e rm da de cada integrante da dupla
## Preencher arquivo dupla.md