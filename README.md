# 🛠️ Projeto ETL: Extração, Transformação e Carga de Dados

Este projeto de ETL foi desenvolvido durante o **Bootcamp de Análise de Dados** e teve como objetivo realizar a extração, tratamento e carga de dados utilizando diversas ferramentas e tecnologias. O projeto simula um fluxo completo de ETL, desde o armazenamento dos dados em nuvem até a inserção em um banco de dados MySQL.

## 🚀 Tecnologias Utilizadas

- **Google Cloud**  
- **Google Colab**  
- **Python (Biblioteca Pandas)**  
- **MySQL**  

## 🔄 Etapas do Projeto

1. **📤 Upload da Base de Dados**  
   - A base de dados foi carregada em um **bucket no Google Cloud Storage** utilizando o Google Colab.

2. **📥 Consumo da Base de Dados**  
   - A base armazenada no bucket foi acessada e carregada novamente no Google Colab para processamento.

3. **🔧 Processamento e ETL**  
   - Utilizando a biblioteca **Pandas**, foi realizada a etapa de ETL (Extração, Transformação e Carga), que incluiu:  
     - Limpeza dos dados.  
     - Tratamento de inconsistências.   

4. **📊 Criação do Banco de Dados**  
   - Após o tratamento, foi criado um banco de dados chamado **Petrobras** no MySQL.  
   - Dentro do banco, foi criada uma tabela chamada **balanco**, contendo todas as colunas do DataFrame processado.

5. **💾 Inserção dos Dados no MySQL**  
   - Os dados transformados foram inseridos diretamente no banco de dados **MySQL** utilizando o Google Colab, fechando o ciclo completo do processo ETL.

## 🔗 Aprendizados e Conclusão

Este projeto proporcionou uma experiência prática no desenvolvimento de um fluxo de ETL, reforçando habilidades em:  
- Manipulação de dados com Python.  
- Integração com serviços de armazenamento em nuvem.  
- Conexão e manipulação de bancos de dados relacionais.

---

Sinta-se à vontade para explorar o código e o passo a passo completo no repositório. 😊


