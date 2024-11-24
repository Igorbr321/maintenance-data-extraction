### Projeto de Coleta e Registro de Dados sobre Manutenções do Corpo de Bombeiros 🚒


Este projeto é uma aplicação de ETL (Extract, Transform, Load) que utiliza Web Scraping com a biblioteca Requests para a extração de dados sobre manutenções realizadas por Bombeiros. Na etapa de transformação (Transform), é aplicado Data Wrangling para estruturar e tratar os dados extraídos. Por fim, na etapa de carregamento (Load), os dados tratados são armazenados em um arquivo CSV. O projeto também conta com uma interface gráfica desenvolvida com a biblioteca ttkbootstrap, permitindo ao usuário inserir a URL do site e o nome da tabela.


🔍 Visão Geral

O projeto é dividido em três componentes principais:

🖥️ Interface Gráfica: Permite ao usuário inserir a URL do site e o nome da tabela, e aciona a extração dos dados.

⚙️ Função de Extração de Dados: Realiza o web scraping, transforma os dados extraídos e os salva em um arquivo CSV.

📦 Script de Configuração: Empacota a aplicação em um executável para facilitar a distribuição
