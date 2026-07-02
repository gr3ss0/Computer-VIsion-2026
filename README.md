# Computer-VIsion-2026
FUB module

https://www.kaggle.com/competitions/amia-public-challenge-2026/overview


### Tip from lecture
- Use transformers by introducing a no-object class.
- Mask out object of interest. If prediction changes, we can be sure, that it's causality. If not, the prediction is based on corealtion (background).
- If we use older architecture, the best we can expect is 0.3. Then he mentioned YOLO for first 40 and Transformers for first 50 in solution ranking.

- lecture 25.6: use automated mixed precision;

### Submssion:
- debug code on our machine, one epoch, two batches, train and validation
- prepare enviroment
- share github with proffesor, he'll run it on institution's server

### Before training
- get the box coordinates right (per image normalization) https://www.kaggle.com/competitions/amia-public-challenge-2026/discussion/691668
- 