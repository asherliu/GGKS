----------
Topk selection based on various packages
------------------

# Compilie:
nvcc -o compareAlgorithms compareAlgorithms.cu  -I./lib/ -I.  -lcurand -lm -lgsl -lgslcblas

# Execution:
./compareAlgorithms

# Dependency:
    libgsl

# Bugfixed:
    syncthreads() --> __syncthreads()

# Credit 
 Tolu Alabi, Jeffrey D. Blanchard, Bradley Gordon, and Russel Steinbach
