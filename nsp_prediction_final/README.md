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
python3 main.py --model ElectraModel --pretrained-class google/electra-large-discriminator --core-lr 5e-5 --tokenizer ElectraTokenizer --batch-size 8
```
```bash
python3 main.py --model DistilBertModel --pretrained-class distilbert-base-uncased --core-lr 5e-5 --tokenizer DistilBertTokenizer

#### Download links to trained NSP heads

```bash
wget --no-check-certificate "https://onedrive.live.com/download?cid=4F5D82F91F52CDA2&resid=4F5D82F91F52CDA2%212680&authkey=AOE62MSqB3X9MLs" -O ft_BertModel_bert-base-uncased_5e-05_0.001.pth
```
```bash
wget --no-check-certificate "https://onedrive.live.com/download?cid=4F5D82F91F52CDA2&resid=4F5D82F91F52CDA2%212681&authkey=AEnPKLYUQE2cafA" -O ft_DebertaModel_microsoft_deberta-base_5e-05_0.001.pth
```
```bash
wget --no-check-certificate "https://onedrive.live.com/download?cid=4F5D82F91F52CDA2&resid=4F5D82F91F52CDA2%212679&authkey=AACYlLxAZEvev_g" -O ft_DistilBertModel_distilbert-base-uncased_5e-05_0.001.pth
```
