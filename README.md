# ERA-SESSION15

### Achieved:
1. **Training Loss: 2.920**
2. **CER Score: 0.691**
3. **BLEU Score: 0.000**
4. **WER Score: 1.080**


### Results
![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/f70df82d-f446-4ada-b2fc-f0b7aa7cde25)

**Note:** Detailed results are presnt in results folder as a CSV file

### Model Summary
```python
   | Name                                    | Type               | Params
--------------------------------------------------------------------------------
0  | transformer                             | Transformer        | 75.1 M
1  | transformer.encoder                     | Encoder            | 18.9 M
2  | transformer.encoder.layers              | ModuleList         | 18.9 M
3  | transformer.encoder.norm                | LayerNormalization | 2     
4  | transformer.decoder                     | Decoder            | 25.2 M
5  | transformer.decoder.layers              | ModuleList         | 25.2 M
6  | transformer.decoder.norm                | LayerNormalization | 2     
7  | transformer.src_embed                   | InputEmbeddings    | 8.0 M 
8  | transformer.src_embed.embedding         | Embedding          | 8.0 M 
9  | transformer.tgt_embed                   | InputEmbeddings    | 11.5 M
10 | transformer.tgt_embed.embedding         | Embedding          | 11.5 M
11 | transformer.src_pos                     | PositionalEncoding | 0     
12 | transformer.src_pos.dropout             | Dropout            | 0     
13 | transformer.tgt_pos                     | PositionalEncoding | 0     
14 | transformer.tgt_pos.dropout             | Dropout            | 0     
15 | transformer.projection_layer            | ProjectionLayer    | 11.5 M
16 | transformer.projection_layer.projection | Linear             | 11.5 M
17 | loss_fn                                 | CrossEntropyLoss   | 0     
18 | cer_metric                              | CharErrorRate      | 0     
19 | wer_metric                              | WordErrorRate      | 0     
20 | bleu_metric                             | BLEUScore          | 0     
--------------------------------------------------------------------------------
75.1 M    Trainable params
0         Non-trainable params
75.1 M    Total params
300.532   Total estimated model params size (MB)
```
### Loss & Other Metrics
**Training Loss:**
![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/ca08c5c5-5315-44a8-b5f1-da9cf0db9702)

**CER, WER & BLEU Score:**
![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/139011c1-187b-4fd6-8d03-3eac18490249)

### Tensorboard Plots 
![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/1747504f-2d38-4da4-bfc5-3c3a5853022a)

![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/c144b6fd-6b73-4374-bfc0-9238e0167293)

![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/19edad0e-ffce-4d66-b8fb-084af39337cd)

![image](https://github.com/Navyabhat03/ERA-V1-Session-15/assets/60884505/3412885f-4cc7-4cde-b53d-271e2372ef9e)



