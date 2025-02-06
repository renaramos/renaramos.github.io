# 4 anos com o amor da minha vida
Oi meu amor, 4 anos atrás eu não podia imaginar que estariamos onde estamos, mas sou muito grata por tudo que passamos juntos até o dia de hoje. Desde o início do nosso relacionamento você quer me ensinar a programar e hoje 4 anos depois, eu programei. Ta bem tosco, mas assisti vídeos e li varios websites para te fazer essa surpresa!

Não posso te garantir a melhor qualidade, mas garanto que fiz com todo o amor do mundo. Eu te amo meu amor e espero que você goste dessa viagem pelos nossos 4 anos de história!

# Carta aberta para Você 
  push:
    branches: ["main"]

# Como esse site vai funcionar:
  workflow_dispatch:

# Prmeira Pergunta
permissions:
  
    runs-on: ubuntu-latest
    needs: build
    steps:
      - name: Deploy to GitHub Pages
        id: deployment
        uses: actions/deploy-pages@v4

theme: jekyll-theme-cayman
