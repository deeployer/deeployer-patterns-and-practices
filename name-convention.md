[Home](http://deeployer.com/deeployer-patterns-and-practices/) > Name Convention

# Name Convention

Neste paper encontram-se as convenções de nomenclatura para criação de projetos no Visual Studio (Code), recursos na Azure, itens no Azure DevOps etc.

**Motivação**

Seguir um conjunto consistente de convenções de nomenclatura no desenvolvimento de uma estrutura pode ser uma grande contribuição para a usabilidade da estrutura. 

Os padrões permitem que a estrutura seja usada por muitos desenvolvedores em projetos e equipes separadas. Além da consistência da forma, os nomes dos elementos  devem ser facilmente compreendidos e devem transmitir inequivocamente sua função/propósito. 

**Regras gerais**

- Utilizar sempre nomes com letras minúsculas.

## Azure

### Resource Group

- **Name convention:** ```<Environment>-<Region>-<BusinessUnitName>-<ProductName>-<Purpose>```
- **Exemplo de uso:** Exemplo de uso: dev.br.deephealth-data-ingest

## Projetos do Visual Studio (Code)

### Azure Functions

- **Name convention:** ```<BusinessUnitName>-<ProductName>-func-<Purpose>```
- **Exemplo de uso:** Exemplo de uso: deephealth-data-func-ftpscan

## Azure DevOps

To-do

## Atlas / MongoDB

### NoSQL database name

- **Name convention:** ```<BusinessUnitName>-<Product>-<Purpose>```
- **Exemplo de uso:** deephealth-data-ftpscan-ingest--control

### NoSQL database collection name

- **Name convention:** ```<SourceName>-<ItemName>```
- **Exemplo de uso:** datasus-cnes