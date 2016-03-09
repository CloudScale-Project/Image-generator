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

4. Create directory ```generated_images``` 

5. Edit file ```populate_images``` and set the following variables according to your needs:

  ```$NUM_ITEMS``` - How many items/books are in database (default: 10000)

  ```$DEST_DIR``` - Directory name where to save generated images

  ```$GEN_CMD``` - Path to ```tpcwIMG``` program for generating the images (default: ImgFiles/tpcwIMG)

6. Generate images with executing the following command:

  ```
  $ ./populate_images
  ```
