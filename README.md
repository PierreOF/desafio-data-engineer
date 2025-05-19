## 📊 Principais Resultados

### Estados com mais vendas
 - SP
 - RJ
 - MG
### Estados com tickets médios mais altos
 - PB
 - AL
 - AC

### Clusters de Clientes por Valor Gasto

**0 Econômicos	R$ 400–700	Muitos clientes, baixo ticket**
**1	Clientes Regulares / VIP	R$ 1.200–2.000+	Menor número, alto valor unitário**
**2	Compradores Oportunos	R$ 100–300	Compras pontuais, dispersos**

### Insights relacionados ao score de avaliações

![image](https://github.com/user-attachments/assets/eac22d73-c365-4ae5-b4f9-42a208ae80f9)

## Visualizações / Dashboard

![image](https://github.com/user-attachments/assets/81168090-44ed-4908-82d6-19621d7840cc)
![image](https://github.com/user-attachments/assets/c5f80337-d65a-466a-b117-7e22d7d27e24)
![image](https://github.com/user-attachments/assets/c5a663f8-186b-46b7-91db-231274e2be53)
![image](https://github.com/user-attachments/assets/e2ac7f6d-faae-4359-b781-0e6d8929f406)



## Requisitos

* Python 3.7+
* Jupyter
* sqlite3

## Instalação



1. Clone o repositório:

   ```bash
   git clone https://github.com/PierreOF/desafio-data-engineer
   cd desafio-data-engineer
   ```

## Setup do ambiente

2. Faça o download do dataset do Kaggle
Link para o dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

3. extraia as tabelas .csv e crie uma pasta chamada /data no diretorio do repositorio
 
## Criando ambiente de execução

   ```bash
   python -m venv venv
   ```

## Acessando o ambiente de execução

Linux (na mesma pasta do venv)
   ```bash
   source venv/bin/activate
   ```

Windows (na mesma pasta do venv)
   ```bash
   venv/scripts/activate
   ```

4. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

5. Execute o arquivo desafio-data-engineer.ipynb com o ambiente do interpretador python corretamente selecionado
