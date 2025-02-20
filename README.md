# Oracle PL/SQL Built-in Functions ~ Ayush

## Overview

This repository contains a detailed reference guide to Oracle PL/SQL built-in functions. These functions are pre-defined by Oracle and are essential for database operations and data manipulation. 
Types of Functions

## Oracle built-in functions are categorized into four main types:
  Column-Level Functions:
  Group Functions   Conversion Functions    General Functions     Column-Level Functions
These functions operate on individual column values and are further divided into:

## Number Functions
     (e.g., ABS(), POWER(), MOD(), SQRT(), SIGN())

## Character Functions 
     (e.g., LOWER(), UPPER(), INITCAP(), LENGTH(), SUBSTR(), REPLACE(), CONCAT())

## Date Functions 
     (e.g., SYSDATE, ADD_MONTHS(), MONTHS_BETWEEN(), NEXT_DAY(), LAST_DAY())

## Group Functions

      Group functions work on a set of rows and return a single aggregated result:

      MIN(), MAX(), SUM(), AVG(), COUNT(), VARIANCE(), STDDEV()**

## Conversion Functions

      Used for data type conversion:

      To Character: TO_CHAR()

      To Date: TO_DATE()

      To Number: TO_NUMBER()

## General Functions

      Applicable to multiple data types:

      GREATEST(), LEAST(), USER(), NVL(), DISTINCT(), SOUNDEX()

## Usage

      All Oracle built-in functions are executed using the SELECT statement. For example:

      SELECT ABS(-100) FROM DUAL; -- Output: 100
      SELECT INITCAP('hello world') FROM DUAL; -- Output: Hello World
      SELECT ADD_MONTHS(SYSDATE, 2) FROM DUAL; -- Adds 2 months to the current date


Feel free to contribute by adding more examples or improving the documentation.

