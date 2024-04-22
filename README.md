# LoRA_KonowledgeDistillation
# Setting Environment
Generate Container
```bash
sudo docker container run -itd  --gpus all --ipc=host --name LoKD python:3.8
sudo docker exec -it LoKD /bin/bash
```
**Git Clone**
```bash
cd root
git clone https://github.com/jo1132/LoKD.git
cd LoKD
```
**Setting Environment**
```bash
bash setup.sh
```
**Download Dataset**
```bash
cd NOAH/data/vtab-source/
rm data/vtab
mkdir data/vtab
python get_vtab1k.py # Some of dataset can be error. You can delete the item of dataset list.
```
