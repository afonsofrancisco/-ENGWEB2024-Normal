# Teste EW Francisco Afonso

## Setup

1. Conversão através de https://csvjson.com/csv2json
1. Criar um arquivo `contratos2024.json` com o conteúdo do json
1. Trocar o nome do campo do identificador para `_id`
1. Correr o script python `convert_dataset.py` para resolver problemas no dataset.
1. Executar o container que já conta com o mongo import

## Import dataset
```bash
mongo-seed-1  | 2024-05-16T14:48:21.399+0000    36377 document(s) imported successfully. 0 document(s) failed to import.
```