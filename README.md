# BizCod
this is a default BizCod repository. 
This repository serves as  astarting point and it will be expanded as the project grows.

```
sdfsdfsd
```

```html
<script src="//unpkg.com/graphre/dist/graphre.js"></script>
<script src="//unpkg.com/nomnoml/dist/nomnoml.js"></script>

<canvas id="target-canvas"></canvas>
<script>
    var canvas = document.getElementById('target-canvas');
    var source = '[nomnoml] is -> [awesome]';
    nomnoml.draw(canvas, source);
</script>
```

## Table of Contents
* [Introduction](#introduction)
* [Structure of BizCod](#structure-of-griddb)
* [Instruction set](#instruction-set)




---							  
# Introduction									 

swdfewrfewrewr

## Purpose of this documentation

This manual is targeted at designers and developers who perform system design and development using GridDB Community Edition.

The contents of this manual are as follows.

  - Structure of GridDB
      - Describes the cluster operating structure in GridDB.
  - The data model of GridDB
      - Describes the data model of GridDB.
  - Functions provided by GridDB
      - Describes the data management functions provided by GridDB.
  - Parameter
      - Describes the parameters to control the operations in GridDB.

## Instruction set

This manual is targeted at designers and developers who perform system design and development using GridDB Community Edition.


#### :warning: Note
- GridDB is a database that manages a group of data (known as a row) that is made up of a key and multiple values. Besides having a composition of an in-memory database that arranges all the data in the memory, it can also adopt a hybrid composition combining the use of a disk (including SSD as well) and a memory. 
- OS user (gsadm) is created when GridDB is installed using the package.


## Terminology

Describes the terms used in GridDB in a list.

| Term                                                | Description                                                                                                                                                                                                                                                                                                                                                                                  |
|--------------------------------|------------------------------------------------------------------------|
| Node                                                | Refers to the individual server process to perform data management in GridDB.                                                                                                                                                                                                                                                                                                                |
| Cluster                                             | Single or a set of nodes that perform data management together in an integrated manner.                                                                                                                                                                                                                                                                                                      |
