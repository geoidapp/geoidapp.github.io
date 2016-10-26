---
assignees:
- adonese

---

## What are the spherical harmonics

GeoidApp uses spherical harmonics as a mathematical representation of the earth. We said earlier that people have used different types of mathematical shapes to define the earth e.g. Sphere. There are a lot to say about spherical harmonics and their derivation. You can see a blog post that we made to demonstrate the concept of spherical harmonics.

* TOC
{:toc}


## GeoidApp basic workflow

We want the user to less worry about many details. We don't need you to just modify everything, but we want you to --when you want-- to be able easily to modify anything you want.
The reason behind this philosophy is that no matter how our preferences can be good, they just can't match everyone use case.

To list all available models
```shell
$ # make sure you are in the application root directory
$ cd path/to/your/application
$ ls -l downloaded-gfc
```
The default actions arguments are
```shell
$ geoidapp.sh MODEL_NAME MAX_DEGREE MIN_DEGREE [list of other arguments]
$ # if you didn't specify the MODEL_NAME MAX_DEGREE MIN_DEGREE, we will use
$ # MODEL_NAME=eigen-6c4, MAX_DEGREE=2190, MIN_DEGREE=10, NUM_MODELS=20
$ # When you specify the model name, we will search the root directory of the application for any other *.gfc files to forbid some conflicts that might happen because of the multiple files.
$ # We will prompt you to either work with that file, or work with your model. If you choose your model we will move the file to `downloaded-gfc' directory. Else, we will continue with the file that was exist in the root directory. When you specify a file name, that is not exist on `downloaded-gfc' directory we will download it from ICGEM website, and after the download is completed we will start working with it.
```


That's not all, but I'm just too tired to complete it for now.
