- Training a GPT-2 model from scratch on a smaller dataset. 
- Learning its internals

#### DistributedDataParallel
- Each process would be assigned a GPU. 
- Each GPU would process slightly different parts of the data. 
- Then we do average of the gradient. 
- `world_size = number of GPUs being used`

#### Datasets: 
- GPT-2 used WebText. Not released. 
- GPT-3 used: Common Crawl, WebText2, Books1, Books2, Wikipedia. 
- FineWeb-Edu: Subset of FineWeb, 1.3 trillion (very high educational content) and 5.4 trillion (high educational content) tokens. 
- We'll work with sample-10BT