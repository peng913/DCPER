# DCPER
The implementation of DCPER: Zero-shot cross-domain slot filling via Domain-aware Comparative prompting with Post-hoc Entity Refining. 

The code for subsequent train.py and retriever.py will be published after the paper is accepted.

## 🔥 Run our Code

Create a new environment with python==3.9
```shell
conda create -n dcper python==3.9
```
Requirements:

Install the requirement packages
```shell
pip install -r requirements.txt
```

### 📚 Dataset
*SNIPS*
```shell
python retriever.py
```

### 🚀 Zero-shot cross-domain about SNIPS

```shell
python train.py 
```
## Notes and Acknowledgments
The implementation is based on [https://github.com/smxiao/RAGSF](https://github.com/smxiao/RAGSF).
If you feel that I have been helpful to you, please cite our paper and the RAGSF paper(DOI: 10.1109/ICASSP49660.2025.10889405).
retrieve_data.zip is a dataset generated during our experiment.But you may need different parameter adjustments to replicate our experiments.
