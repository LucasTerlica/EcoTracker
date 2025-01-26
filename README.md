# Ecotracker

Este projeto é uma aplicação web desenvolvida em Flask para visualizar e analisar a distribuição geográfica de espécies com base em dados da API GBIF. Inclui funcionalidades de geração de mapas, visualização de dados e comparação entre espécies.

## 📑 Funcionalidades

- **Mapa de Ocorrências:** Visualize a distribuição geográfica de uma espécie com base em filtros opcionais.
- **Comparação de Espécies:** Compare a distribuição de várias espécies em um único mapa.
- **Top 10 Espécies:** Descubra as 10 espécies mais avistadas em um determinado país.
- **Visualização de Dados:** Analise a distribuição temporal das ocorrências de uma espécie com gráficos e tabelas.

## 🚀 Tecnologias Utilizadas

- **Backend:** Flask
- **Frontend:** Jinja2 (HTML), CSS
- **APIs:** GBIF (Global Biodiversity Information Facility)
- **Mapas:** Folium
- **Gráficos:** Matplotlib
- **Serviços:** Docker, Docker Compose, Lighttpd

## ⚙️ Como Executar o Projeto

1. Clone o repositório no GitLab.
2. Construa e inicie os containers utilizando `docker-compose up --build`.
3. Acesse a aplicação no navegador através de `http://localhost:5000`.
4. Execute os testes, caso necessário, utilizando `pytest`.

## 🐛 Relatar Problemas

Se encontrar algum problema, por favor, abra uma issue no repositório do GitLab.

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Consulte o ficheiro `LICENSE` para mais informações.

---

Desenvolvido com ❤️ por Lucas Terlica e Joana Caetano.

