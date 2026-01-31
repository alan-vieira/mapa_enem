# 🌍 DataViz: Mapas Interativos e Análise Geoespacial (Plotly)

## 📖 Descrição do Módulo

Este repositório apresenta a camada visual e interativa do projeto ENEM. O foco aqui foi transformar as médias de desempenho calculadas em insights geográficos, permitindo visualizar como a educação evoluiu em cada estado brasileiro ao longo de mais de uma década.

## 🖼️ Visualização do Desempenho Regional

<div align="center">
  <h3>🗺️ Distribuição Geográfica das Médias de Desempenho (Brasil)</h3>
  <img src="https://raw.githubusercontent.com/alan-vieira/mapa_enem/main/mapa_matematica.png" width="800px">
  <p><i>Visualização interativa gerada com Plotly demonstrando a variação regional das notas.</i></p>
</div>

## 🚀 Diferenciais Técnicos do Projeto

1. **Mapas Coropléticos Dinâmicos**

Diferente de mapas estáticos, utilizei a biblioteca Plotly para criar visualizações onde o usuário pode interagir com os dados de cada estado, visualizar valores exatos ao passar o mouse (hover) e comparar regiões de forma intuitiva.

2. **Análise Temporal (Animation Frames)**

Implementação de uma linha do tempo interativa dentro do próprio mapa. Com um único "Play", é possível observar o deslocamento das médias de desempenho (Matemática e Linguagens) pelo mapa do Brasil entre 2009 e 2021, facilitando a identificação de tendências regionais.

3. **Integração GeoJSON**

Tratamento e integração de arquivos de geometria (JSON) com os microdados do ENEM, garantindo a precisão das fronteiras estaduais e a correta plotagem das métricas.

## 📊 O que este módulo responde?

- Quais estados apresentaram o maior crescimento nas médias de Matemática na última década?

- Como se comportam as disparidades regionais (Norte/Nordeste vs Sul/Sudeste) ao longo do tempo?

- Existe uma correlação visual entre a localização geográfica e o desempenho escolar?

## 📁 Conteúdo

`mapa_plotly_ano.ipynb`: Implementação da lógica de visualização e renderização dos mapas.

## 📺 Veja em Ação

Como os mapas do Plotly são interativos e muitas vezes pesados para renderizar diretamente no GitHub, gravei uma demonstração do funcionamento:

🔗 [Vídeo: Construção de Mapas Interativos com Plotly](https://www.youtube.com/watch?v=uz9ttVOcBjo)

👤 Autor

**Alan Vieira** - *Engenheiro de Telecomunicações & Especialista em Dados*

- [LinkedIn](https://www.linkedin.com/in/alansilvavieira)

- [GitHub Portfólio](https://github.com/alan-vieira)
