Description:
A multi threads C++ programs with Cuda to find the max of matrix and particles nearby 


Part a

1.Set up:
Install Cuda for enviroment

2.To compile, run the following command on server:
nvcc MaxCol.cu -o MaxCol

3.To run,run the following command on server:
./MaxCol [matrixSize] [threads]
ex: ./MaxCol 1024 8


Part b

1.Set up:
Install Cuda for enviroment

2.To compile, run the following command on server:
nvcc findRedsGPU.cu -o findRedsGPU

3.To run, run the following command on server:
./findRedsGPU



