.. Copyright 2010-2018 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

====================
Managing |IAM| Users
====================

.. meta::
   :description: Create, list, update, or retrieve info about |IAM| users.
   :keywords: |IAMlong|, |sdk-php| examples

An |IAM| user is an entity that you create in AWS to represent the person or service that uses it to interact with AWS. A user in AWS consists of a name and credentials.

The examples below show how to:

* Create a new |IAM| user using :aws-php-class:`CreateUser </api-iam-2010-05-08.html#createuser>`.
* List |IAM| users using :aws-php-class:`ListUsers </api-iam-2010-05-08.html#listusers>`.
* Update an |IAM| user using :aws-php-class:`UpdateUser </api-iam-2010-05-08.html#updateuser>`.
* Retrieve info about an |IAM| user using :aws-php-class:`GetUser </api-iam-2010-05-08.html#getuser>`.
* Delete an |IAM| user using :aws-php-class:`DeleteUser </api-iam-2010-05-08.html#deleteuser>`.

All the example code for the |sdk-php| is available `here on GitHub <https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/php/example_code>`_.

Credentials
-----------

Before running the example code, configure your AWS credentials, as described in :doc:`guide_credentials`.

Create an |IAM| User
--------------------

**Imports**

.. literalinclude::  example_code/iam/CreateUser.php
   :lines: 15-18
   :language: php

**Code**

.. literalinclude:: example_code/iam/CreateUser.php
   :lines: 27-42
   :language: php


List |IAM| Users
----------------

**Imports**

.. literalinclude::  example_code/iam/ListUsers.php
   :lines: 15-18
   :language: php

**Code**

.. literalinclude:: example_code/iam/ListUsers.php
   :lines: 27-39
   :language: php

Update an |IAM| User
--------------------


**Imports**

.. literalinclude::  example_code/iam/UpdateUser.php
   :lines: 15-18
   :language: php

**Code**

.. literalinclude:: example_code/iam/UpdateUser.php
   :lines: 27-43
   :language: php

Get Info about an |IAM| User
----------------------------

**Imports**

.. literalinclude::  example_code/iam/GetUser.php
   :lines: 15-18
   :language: php

**Code**

.. literalinclude:: example_code/iam/GetUser.php
   :lines: 27-41
   :language: php

Delete an |IAM| User
--------------------

**Imports**

.. literalinclude::  example_code/iam/DeleteUser.php
   :lines: 15-18
   :language: php

**Code**

.. literalinclude:: example_code/iam/DeleteUser.php
   :lines: 27-42
   :language: php