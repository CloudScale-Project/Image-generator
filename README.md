## Introduction

ImgGen is used in the original TPC-W implementation by the Transaction Processing Performance Council for the generation of static material for the benchmarking application.
It makes use of the gs graphics library version 1.7.2, and parts of the libjpeg version 6b. Their respective licenses, both open source compatible with EPL.

You will find licensing information on the readme files at each directory.

## Usage

1. Change current working directory to ```ImgFiles```:

  ```
  $ cd ImgFiles/
  ```
  
2. Compile files

  ```
  $ make
  ```
  
3. Change current working directory to parent:

  ```
  $ cd ../
  ```

4. Create directory ```generated_images``` and run ```populate_images``` script:

  ```
  $ mkdir generated_images; ./populate_images
  ```
