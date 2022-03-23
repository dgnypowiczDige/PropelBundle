PropelBundle
============

[![Build Status](https://travis-ci.org/propelorm/PropelBundle.svg?branch=4.0)](https://travis-ci.org/propelorm/PropelBundle)

This is the official implementation of [Propel](http://www.propelorm.org/) in Symfony.

## Branching model

As `Propel2` will be released in the near future, we are migrating the branching model of this bundle in advance!

* The `1.0` branch contains Propel *1.6* integration for Symfony *2.0* (*currently 2.0 branch*).
* The `1.1` branch contains Propel *1.6* integration for Symfony *2.1* (*currently 2.1 branch*).
* The `1.2` branch contains Propel *1.6* integration for Symfony *2.2* (*currently master branch*).
* The `2.0` branch contains `Propel2` integration for Symfony *2.5-2.8*.
* The `3.0` branch contains `Propel2` integration for Symfony *2.8-3.x*.
* The `4.0` branch contains `Propel2` integration for Symfony *3.4-4.x*.
* The `5.0` branch contains `Propel2` integration for Symfony **4.x|5.x**.
* The `6.0` branch contains `Propel2` integration for Symfony **6.x**.

## Version 5.0 Changes
* PHP 7.2+ support is added
* support for **s4+** no bundle dir structure is added(Bundle dir structure also work)
* XML/YML schema directory: **project_root/config**

tested with symfony **4.4, 5.0, 5.1, 5.2** and PHP **7.2 - 8.0**

## Symfony 5.0 Installation
### Requirements
- php: 7.2+
- propel/propel

### Composer command
- composer require propel/propel "2.0.0-beta1"
- composer require skyfox/propel-bundle "5.0.0" or "5.0.x-dev"

### composer.json -> add in "require"
- "propel/propel": "2.0.0-beta1"
- "skyfox/propel-bundle": "5.0.0" or "5.0.x-dev"

## Features

 * Generation of model classes based on an XML schema (not YAML) placed under `BundleName/Resources/*schema.xml`;
 * Insertion of SQL statements;
 * Runtime autoloading of Propel and generated classes;
 * Propel runtime initialization through the XML configuration;
 * [Propel Migrations](http://propelorm.org/documentation/09-migrations.html);
 * Reverse engineering from [existing database](http://propelorm.org/documentation/cookbook/working-with-existing-databases.html);
 * Integration to the Symfony Profiler;
 * Load SQL, YAML and XML fixtures;
 * Create/Drop databases;
 * Integration with the Form component;
 * Integration with the Security component;
 * Propel ParamConverter can be used with Sensio Framework Extra Bundle.

[Read the documentation](http://propelorm.org/documentation/)

For license, see:

    Resources/meta/LICENSE
