[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Grupo 2 | Turma: 1102 - Programa Vem Ser Tech Dados - ADA | Módulo 4 - Técnicas de Programação I (PY)  </sub> 


# **Projeto - Análise Explorátoria dos Dados do Airbnb - Paris 🗼**


<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1198980222389858464/thumb2-eiffel-tower-paris-champs-elysees-evening-paris-landmarks.jpg?ex=65c0e058&is=65ae6b58&hm=f80a94468a74b3b1a7104c55299392e769903121900d57137b15ad90714dccf4&" alt="capa" width="400" height="300">
  </a>
</p>



## Análise Explorátoria dos Dados do Airbnb - Paris 

Bem-vindos(as) ao nosso repositório do 4ª projeto desenvolvido durante o curso 'Vem Ser Tech Dados' da ADA Tech. Este repositório reflete o progresso e aprendizado conquistados ao longo do módulo de Técnica de Programação I (PY). Tem como foco a realização de um **EDA** (Exploratory Data Analysis) com os conhecimentos obtidos (Pandas e Numpy).

Vale ressaltar que todos os dados são exclusivamente para fins de demonstração, garantindo total privacidade e conformidade ética.

**Integrantes**:

- [José Truta](https://www.linkedin.com/in/jos%C3%A9-truta/)
- [Igor Cruz](https://www.linkedin.com/in/igorcruzcf/?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
- [Matheus Reis](https://www.linkedin.com/in/matheusreisn/)
- [Leticia Carneiro](https://www.linkedin.com/in/leticia-oliv/)
- [Sarah Rezende](https://www.linkedin.com/in/sarahfrezende/)

**Professor**: 
- [Bruno Issamo](https://www.linkedin.com/in/bruno-issamo-7a977311a/)

## Visão Geral do Projeto 

🔍Este projeto tem como foco a **análise exploratória de dados** relacionados à cidade de Paris, França, utilizando informações disponibilizadas pelo [Inside Airbnb](http://insideairbnb.com/get-the-data/). O objetivo principal é extrair percepções e conhecimentos a partir desses dados, explorando aspectos relevantes do mercado de hospedagem na cidade.

💻 O contexto envolve a simulação de uma empresa fictícia chamada **RotaVIP**, especializada em roteiros de viagem personalizados. Neste caso, nós da RotaVIP fomos contratados pela **EuroTrip**, uma empresa de excursões pela Europa, para desenvolver um **roteiro exclusivo** para a cidade de **Paris**. 

🗺️ Como analista de Dados da **RotaVIP**, realizamos uma Análise Exploratória de Dados (EDA) dedicada à cidade de Paris, com ênfase na área de hotelaria. A equipe utilizou dados do **Airbnb**, uma plataforma global que conecta anfitriões e viajantes. O Airbnb, conhecido por promover transparência e democratização dos dados, disponibiliza informações valiosas através do portal [Inside Airbnb](http://insideairbnb.com/get-the-data/).

## Dados 

Os dados que utilizaremos foram adquiridos de um arquivo CSV disponibilizado no [Inside Airbnb](http://insideairbnb.com/get-the-data/). Os **arquivos** usados aqui tambem podem ser adquiridos em nosso [repositório]() do Github:

- **Listagem** - Informações resumidas e métricas  (bom para visualizações): [listings.csv](https://)


### **Dicionário de Variavéis**

- `id`: Identificador único para cada listagem no Airbnb, distinguindo cada propriedade individualmente.
- `name`: Nome da propriedade anunciada.
- `host_id`: Identificador único para o anfitrião (host) da propriedade.
- `host_name`: Nome do anfitrião 
- `neighbourhood_group`: Subdivisão geográfica mais ampla, como um distrito ou bairro.
- `neighbourhood`: Nome do bairro/ Distrito.
- `latitude`: Coordenada de latitude da localização da propriedade.
- `longitude`: Coordenada de longitude da localização da propriedade.
- `room_type`: Tipo de quarto ou unidade anunciada (por exemplo, "Casa inteira", "Quarto privado", "Compartilhado").
- `price`: Valor do aluguel da propriedade por noite.
- `minimum_nights`: Número mínimo de noites que um hóspede deve reservar para esta propriedade.
- `number_of_reviews`: Total de avaliações que a propriedade recebeu de hóspedes anteriores.
- `last_review`: Data da última avaliação/revisão deixada por um hóspede.
- `reviews_per_month`: Média de avaliações/revisões que a propriedade recebe por mês.
- `calculated_host_listings_count`: Número total de propriedades que o host possui, calculado automaticamente.
- `availability_365`: Número de dias em que a propriedade está disponível para reserva ao longo do ano.
- `number_of_reviews_ltm`: Número de avaliações que a propriedade recebeu nos últimos doze meses.
- `license`: Possível licença ou autorização associada à propriedade.

<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1198977694004682752/cats.jpg?ex=65c0ddfe&is=65ae68fe&hm=7592e55b8862cbda52a303953ee10fdf3f357eb049f96977e08b99ddb85545b7&" alt="capa" width="400" height="300">
  </a>
</p>
