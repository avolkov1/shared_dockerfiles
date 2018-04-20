## Dockerfiles for Reference

Publish and share dockerfiles for reference.


### Tensorflow Dockerfiles

* [Dockerfile.tf18.03\_ssh](tensorflow/v1.4.0-nvcr/Dockerfile.tf18.03_ssh)

    Tensorflow container with ssh client and server installed. This enables
    the container to be run in multinode setups with MPI (Horovod installed)
    via docker.


### BVLC Caffe Dockerfile

* [Dockerfile.caffe\_gpu](bvlc_caffe/Dockerfile.caffe_gpu)

    BVLC Caffe container built against CUDA 9 and NCCL2. Added Volta
    architecture support via CUDA 9 and cmake option 70
    `set(Caffe_known_gpu_archs "30 35 50 60 61 70")`.


### TODO: Document the other containers
