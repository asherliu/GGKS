----------
Topk selection based on various packages
------------------

# Compilie:
nvcc -o compareAlgorithms compareAlgorithms.cu  -I./lib/ -I.  -lcurand -lm -lgsl -lgslcblas

---
Solutions to customize the source for your use
---------
The main function in **compareAlgorithms.cu** demonstrates how to use **timeBucketSelect**. Other funcions tends to similar.  

# Execution:
./compareAlgorithms

# Dependency:
    libgsl

# Bugfixed:
    syncthreads() --> __syncthreads()

# Credit 
 Tolu Alabi, Jeffrey D. Blanchard, Bradley Gordon, and Russel Steinbach
