# FA22-255-Data-Mining

`LSH` - Implememted python code to perform traditional LSH 

Step1: Generate shingles of any length (I took k=2)
Step2: Create a vocabulary list
Step3: Perform one-hot encoding on texts based on vocabulary list.
Step4: Use random numbers and hash to a lower dimension to generate signatures.
Step5: Hash those signatures into to bands.
Step6: Parse through each band to find candidate pair.
Step7: Candidate pairs will be generated which are of similar.

'LSH_Random Projections` - Implemented python code to perform LSH with random projections.

Step1: Using random library consider hyper planes(random projections).
Step2: Take data points of any dimension. eg:2-D
Step3: Project those points against hyper planes.
Step4: Assign 1 if the point is towards the direction of hyper-plane and 0 on opposite side.
Step5: Hash the data values in to buckets, so that points which are similar fall into same bucket.

`FAISS Library` - Used FAISS(Facebook AI) to find similarity between movies.

* Found the similarity between movies using Exhaustive search, Product quantization, Trees ansd Forests and HNSW algorithms.
