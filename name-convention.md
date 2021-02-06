[Home](http://deeployer.com/deeployer-patterns-and-practices/) > Name Convention

# Name Convention

Neste paper encontram-se as convenções de nomenclatura para criação de projetos no Visual Studio (Code), recursos na Azure, itens no Azure DevOps etc.

**Motivação**

Seguir um conjunto consistente de convenções de nomenclatura no desenvolvimento de uma estrutura pode ser uma grande contribuição para a usabilidade da estrutura. 

Os padrões permitem que a estrutura seja usada por muitos desenvolvedores em projetos e equipes separadas. Além da consistência da forma, os nomes dos elementos  devem ser facilmente compreendidos e devem transmitir inequivocamente sua função/propósito. 

**Regras gerais**

- Utilizar sempre nomes com letras minúsculas, os temos entre "<>" estão utilizando Pascal Case apenas para legibilidade;
- Termos que não estiverem entre "<>" são fixos e obrigatórios no nome;
- Não utilizar abreviações, que muitas vezes podem gerar confusões no entendimento;
- Não utilizar acrônimos, a menos que sejam amplamente reconhecidos e aceitos.

## Azure

### Resource Group

- **Name convention:** ```<Environment>-<Region>-<BusinessUnitName>-<ProductName>-<Purpose>```
- **Exemplo de uso:** dev-br-deephealth-data-ingest

## Projetos do Visual Studio (Code)

### Azure Functions

- **Name convention:** ```<BusinessUnitName>-<ProductName>-func-<Purpose>```
- **Exemplo de uso:** deephealth-data-func-ftpscan

### Azure Storage Account

- **Name convention:** ```<BusinessUnitName>-<ProductName>-<Purpose>```
- **Exemplo de uso:** deephealth-data-ingest

### Azure Storage Account - Queue

- **Name convention:** ```<StorageAccountName>-<Purpose>-in```
- **Name convention:** ```<StorageAccountName>-<Purpose>-poison```
- **Exemplo de uso:** deephealth-data-ingest-download-in

## Azure DevOps

To-do

## Atlas / MongoDB

### NoSQL database name

- **Name convention:** ```<BusinessUnitName>-<Product>-<Purpose>```
- **Exemplo de uso:** deephealth-data-ftpscan-ingest--control

### NoSQL database collection name

- **Name convention:** ```<SourceName>-<ItemName>```
- **Exemplo de uso:** datasus-cnes