## Dockerfiles for Reference

Publish and share dockerfiles for reference.


### Tensorflow Dockerfiles

* [Dockerfile.tf18.03\_tf1.4.0\_ssh](tensorflow/v1.4.0-nvcr/Dockerfile.tf18.03_ssh)

    Tensorflow container with ssh client and server installed. This enables
    the container to be run in multinode setups with MPI (Horovod installed)
    via docker.

* [Dockerfile.tf1.7.0py2\_cuda9.1\_cudnn7\_nccl2.1.15\_hvd\_ompi3\_ibverbs](tensorflow/v1.7.0/Dockerfile.tf1.7.0py2_cuda9.1_cudnn7_nccl2.1.15_hvd_ompi3_ibverbs)

    Tensorflow v1.7.0 (with CUDA 9.1) with ssh client and server installed. This
    enables the container to be run in multinode setups with MPI (Horovod
    installed) via docker.


### BVLC Caffe Dockerfile

* [Dockerfile.caffe\_gpu](bvlc_caffe/Dockerfile.caffe_gpu)

    BVLC Caffe container built against CUDA 9 and NCCL2. Added Volta
    architecture support via CUDA 9 and cmake option 70
    `set(Caffe_known_gpu_archs "30 35 50 60 61 70")`.


### TODO: Document the other containers
