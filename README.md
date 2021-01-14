# BizDev

BizDev is a suite of products that enable the development of Enterprise Application Software Fabric (EAS/F) in Rexi environment.

It is Rexi based and can only run in Rexi environment. For more information about Rexi Operating System please refer to this publication.


```
define model Bank
    id ID,
    name Text fact,
    account (Account)* [1:n]
;
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

This manual is targeted at <b>designers</b> and developers who perform system design and development using GridDB Community Edition.


#### :warning: Note
- GridDB is a database that manages a group of data (known as a row) that is made up of a key and multiple values. Besides having a composition of an in-memory database that arranges all the data in the memory, it can also adopt a hybrid composition combining the use of a disk (including SSD as well) and a memory. 
- OS user (gsadm) is created when GridDB is installed using the package.


## Terminology

Describes the terms used in GridDB in a list.


| Term                           | Description   |
|--------------------------------|------------------------------------------------------------------------|
| main-frame                     | Top level Main frame UI class                                          | 
| main-frame                     | Top level Main frame UI class                                          | 
| main-frame                     | Top level Main frame UI class                                          | 
| main-frame                     | Top level Main frame UI class                                          | 
| main-frame                     | Top level Main frame UI class                                          | 



#### You can use Apollo Server as:

* A stand-alone GraphQL server, including in a serverless environment
* An add-on to your application's existing [Node.js middleware](./integrations/middleware/) (such as Express or Fastify)
* A gateway for a [federated data graph](https://www.apollographql.com/docs/federation/)

#### Apollo Server provides:

*  **Straightforward setup**, so your client developers can start fetching data quickly
*  **Incremental adoption**, allowing you to add features as they're needed
*  **Universal compatibility** with any data source, any build tool, and any GraphQL client
*  **Production readiness**, enabling you to ship features faster

#### Ready to try it out?

import {Button} from '@apollo/space-kit/Button';
import {Link} from 'gatsby';

<div align="center">
  <Button as={<Link to="/getting-started/" />} size="large">
    Get started!
  </Button>
</div>
