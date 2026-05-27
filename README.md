# _quarto.yml

project:
  type: website

website:
  title: "Voyage Doré"
  
  navbar:
    background: dark
    left:
      - href: index.qmd
        text: Home
      - href: destinations.qmd
        text: Destinations
      - href: about.qmd
        text: About

format:
  html:
    theme: darkly
    css: styles.css
    toc: false
