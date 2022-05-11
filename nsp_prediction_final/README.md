```bash
python3 main.py --model DebertaModel --pretrained-class microsoft/deberta-base --core-lr 5e-5 --tokenizer DebertaTokenizer --saved-model ./trained_models/ft_DebertaModel_microsoft_deberta-base_5e-05_0.001.pth --test
```
```bash
python3 main.py --model DebertaModel --pretrained-class microsoft/deberta-base --core-lr 5e-5 --tokenizer DebertaTokenizer
```
```bash
python3 main.py --model BertModel --pretrained-class bert-base-uncased --core-lr 5e-5 --tokenizer BertTokenizer --saved-model ./trained_models/ft_BertModel_bert-base-uncased_5e-05_0.001.pth --test
```
```bash
python3 main.py --model BertModel --pretrained-class bert-base-uncased --core-lr 5e-5 --tokenizer BertTokenizer
```
```bash
python3 main.py --model ElectraModel --pretrained-class google/electra-large-discriminator --core-lr 5e-5 --tokenizer ElectraTokenizer
```
```bash
python3 main.py --model DistilBertModel --pretrained-class distilbert-base-uncased --core-lr 5e-5 --tokenizer DistilBertTokenizer
```
