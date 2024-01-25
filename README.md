[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Grupo 2 | Turma: 1102 - Programa Vem Ser Tech Dados - ADA | Módulo 4 - Técnicas de Programação I (PY)  </sub> 


# **Projeto - Análise Explorátoria dos Dados do Airbnb - Paris 🗼**


<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1198980222389858464/thumb2-eiffel-tower-paris-champs-elysees-evening-paris-landmarks.jpg?ex=65c0e058&is=65ae6b58&hm=f80a94468a74b3b1a7104c55299392e769903121900d57137b15ad90714dccf4&" alt="capa" width="400" height="300">
  </a>
</p> <p align="center"> <sup> Foto: Torre Eiffel - Fonte: BesthHqWallpapers </sup> </p>



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

# **Conlcusão**

**Acerca do Dataset**

- Durante a análise do conjunto de dados do Airbnb, identificamos uma condensação de informações na coluna '**name**', incluindo elementos como **score** de **avaliação**, **quantidade de quartos**, **camas** e **banheiros**. Optamos por destacar esses elementos e criar novas colunas específicas para cada informação relevante.

- Ao explorar a qualidade dos dados, observamos a presença de valores ausentes em várias colunas, sendo a coluna 'neighbourhood_group' a que possui 100% dos valores faltantes. Para garantir a robustez e confiabilidade das análises, aplicamos estratégias como preenchimento de dados ausentes, eliminação de colunas irrelevantes e outras técnicas de imputação, conforme necessário.

- Decidimos excluir colunas como 'last_review' e 'license', cuja ausência não impacta a continuidade da análise. A coluna 'neighbourhood_group' também foi removida por não apresentar informações úteis.

- A análise também destaca uma variação
significativa nas médias de preços dentro de cada bairro, refletindo a diversidade de imóveis disponíveis, desde apartamentos pequenos até grandes mansões. Essa variação é crucial para os usuários do Airbnb, permitindo que encontrem acomodações que atendam às suas necessidades e orçamento específicos.

- **Preço mínimo**: 💶 **€ 10** (equivalente a **R$ 54,30**)

- **Preço máximo**: 💶 **€ 1.999** (cerca de **R$ 10.854.57**)

- **A média de preços em Paris** :💶 **€ 204.91** (cerca de**R$ 1.112,62**)

**Acerca dos outliers**

Ao investigar possíveis outliers, notamos que a coluna 'price' e 'minimum_nights' poderiam conter valores discrepantes. Após o tratamento adequado desses outliers, realizamos uma análise mais aprofundada dos preços médios por bairro, destacando os mais caros e baratos. Além disso, identificamos o menor e o maior preço por bairro, proporcionando insights valiosos sobre a variação de preços.

**Acerca da EDA **

A análise do tipo de imóvel disponível revelou uma preferência significativa por casas/apartamentos inteiros **67%**, seguidos por quartos privativos 7%. Os quartos de hotel, apesar de representarem uma parcela menor 0.83%, tendem a ser consistentemente os mais caros, indicando uma preferência por acomodações mais exclusivas e personalizadas.

**Problema de negócio**

Concluímos que a plataforma Airbnb oferece uma ampla diversidade de tipos de imóveis e faixas de preços, desde opções mais acessíveis até acomodações de luxo. Essa variedade é altamente benéfica para a Rota VIP, pois permitirá a criação de roteiros turísticos personalizados, alinhados aos interesses e orçamento específicos de cada cliente.

Essa abordagem não apenas atende às necessidades variadas dos clientes da Rota VIP, mas também estabelece uma parceria estratégica com o Airbnb. Ao apresentar uma gama diversificada de opções e preços acessíveis, podemos aumentar a visibilidade da Rota VIP, enquanto o Airbnb se beneficia ao incentivar mais pessoas a utilizarem seus serviços.

Ao posicionar o Airbnb como nosso parceiro exclusivo para oferecer comodidade aos clientes, criamos uma sinergia que não apenas fortalece a visibilidade da Rota VIP, mas também proporciona ao Airbnb uma vantagem competitiva ao ser a escolha preferencial para acomodações personalizadas e serviços turísticos. Essa colaboração estratégica pode resultar em benefícios mútuos, promovendo a oferta de experiências turísticas sob medida e incentivando o uso contínuo dos serviços do Airbnb.

<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1198977694004682752/cats.jpg?ex=65c0ddfe&is=65ae68fe&hm=7592e55b8862cbda52a303953ee10fdf3f357eb049f96977e08b99ddb85545b7&" alt="capa" width="400" height="300">
  </a>
</p><p align="center"> <sup> Foto: Mapa dos bairros de Paris - Fonte: Paris CityVision </sup> </p>
