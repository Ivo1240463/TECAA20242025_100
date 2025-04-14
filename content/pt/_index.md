---
title: 'Início'
date: 2025-03-19
type: landing

design:
  # Espaçamento padrão da seção
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Princípio 1 - Perceptível
      text: Diretrizes de Acessibilidade para Conteúdo da Web (WCAG)
      primary_action:
        text: Diretrizes
        url: /diretrizes/
        icon: rocket-launch
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # Para tela inteira, adicione `min-h-screen` abaixo
      css_class: ""
      background:
        color: ""
        text_color_light: true
        image:
          # Adicione sua imagem de fundo em `assets/media/`.
          filename: "home-hero.jpg"
          focal_point: "Topo"
          filters:
            brightness: 0.2
  
  - block: stats
    content:
      items:
        - statistic: "1.3B+"
          description: |
            População mundial  
            com deficiências  
            em 2024
        - statistic: "40k+"
          description: |
            Sites empresariais
        - statistic: "3%"
          description: |
            São acessíveis   
            para a comunidade de deficientes
    design:
      # Cor de fundo da seção (classe CSS)
      css_class: "bg-gray-100 dark:bg-gray-800"
      # Reduzir espaçamento
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  
  - block: features
    content:
      title: O que é WCAG? 
      text: "As **Diretrizes de Acessibilidade para Conteúdo da Web (WCAG)** foram desenvolvidas com o objetivo de fornecer um padrão único compartilhado para a acessibilidade de conteúdo web que atenda às necessidades de indivíduos, organizações e governos a nível internacional. O WCAG ajuda a criar conteúdo web que seja mais acessível para pessoas com deficiência. Este padrão é composto por 4 princípios: **Perceptível**, **Operável**, **Compreensível** e **Robusto**."
    design: 
      spacing:
        padding: ["5rem", 0, 0, 0]
  
  - block: features
    content:
      title: Princípio 1 - Perceptível
      text: Este é o primeiro princípio do WCAG, cujo objetivo é apresentar informações e componentes de interface de usuário de maneira que os usuários possam **perceber**. Isso significa que a informação apresentada aos usuários **não pode ser invisível a todos os seus sentidos**.
      items:
        - name: Alternativas de Texto
          icon: document-text
          description: Fornecer **alternativas de texto** para qualquer **conteúdo não textual** para que possa ser transformado em outras formas que as pessoas precisam, como impressão em grande formato, braille, fala, símbolos ou linguagem mais simples.
        - name: Mídia Baseada no Tempo
          icon: camera
          description: Fornecer **alternativas** para **mídia baseada no tempo**.
        - name: Adaptável
          icon: view-columns
          description: Criar conteúdo que possa ser apresentado de diferentes maneiras (por exemplo, layout mais simples) **sem perder informação ou estrutura**.
        - name: Distinguível
          icon: speaker-wave
          description: Tornar **mais fácil** para os usuários verem e **ouvirem o conteúdo**, incluindo separar o primeiro plano do fundo.
    design: 
      spacing:
        margin: [0, 0, 0, 0]
        padding: [0, 0, 0, 0]
---
