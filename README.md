Test GPU / CPU Speed

https://medium.com/@andriylazorenko/tensorflow-performance-test-cpu-vs-gpu-79fcd39170c


git clone https://github.com/tensorflow/models.git

cd models/tutorials/image/cifar10

python cifar10_train.py

Test notes:

1. 2 x AMD Opteron 6168 -> ~440 examples/sec
2. i7–7500U -> 115 examples/sec
3. GeForce 940MX -> 1190 examples/sec
4. GeForce 1070 -> 6000~7000 examples/sec, 
