# Quantize huggingface models

see `huggingface-tweet.ipynb` for the implementation.

we quantize distilbert for test, but you can swap to any models.

| Quantized bit | F1    |
|---------------|-------|
| 4             | 0.71  |
| 5             | 0.73  |
| 6             | 0.745 |
| 7             | 0.75  |
| 8             | 0.75  |
| Full          | 0.76  |