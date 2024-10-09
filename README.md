# PostgreSQL-String-Functions

## This repository contains important and useful string functions in PostgreSQL database.

## `String Functions:-`

### String functions are used to examining and manipulating string values. Strings in this context include values of the types character, character varying, and text.

##### Please follow this link to learn more about string functions.

https://www.postgresql.org/docs/9.1/functions-string.html

## Here are some most commonly used string functions are given below:-

### 1) `CONCAT:-`

#### It is used to concatenate (combine) the given strings. For example:-

```
SELECT CONCAT ('HELLO ', 'WORLD');
```

We can also use like this.

```
SELECT CONCAT ('HELLO', '-' , 'WORLD');
```

### 2) `CONCAT_WS:-`

#### It is used to concatenate and also separate the given strings. For example:-

```
SELECT CONCAT_WS (' :: ' ,'HELLO ', 'WORLD');
```

### 3) `LENGTH:-`

#### It is used to check the length of a string. For example:-

```
SELECT LENGTH ('HELLO');
```

### 3) `SUBSTR OR SUBSTRING:-`

#### It is used to extract part of a string. For example:-

```
SELECT SUBSTR ('HELLO');
```

```
SELECT SUBSTRING ('HELLO');
```

### 4) `TRIM:-`

#### It is used to remove spaces from both left and right of string. For example:-

```
SELECT TRIM ('   HELLO     ');
```

### 5) `LTRIM:-`

#### It is used to remove spaces from only left of string. For example:-

```
SELECT LTRIM ('           HELLO');
```

### 6) `RTRIM:-`

#### It is used to remove spaces from only right of string. For example:-

```
SELECT RTRIM ('HELLO             ');
```

### 7) `REPLACE:-`

#### It is used to replace a string from another string. For example:-

```
SELECT REPLACE ('HY FAROOQ', 'Hy', 'Hello' );
```

### 8) `REPLACE:-`

#### It is used to replace a string from another string. For example:-

```
SELECT REPLACE ('HY FAROOQ', 'Hy', 'Hello' );
```

### 9) `REVERSE:-`

#### It is used to reverse a string. For example:-

```
SELECT REVERSE ('HY FAROOQ');
```

### 10) `UPPER:-`

#### It is used to convert a string to uppercase. For example:-

```
SELECT UPPER ('HY FAROOQ');
```

### 11) `LOWER:-`

#### It is used to convert a string to lowercase. For example:-

```
SELECT LOWER ('HY FAROOQ');
```

### 12) `LEFT:-`

#### It is used to extract a part of string from left side of given string. For example:-

```
SELECT LEFT ('HY FAROOQ', '6');
```

### 13) `RIGHT:-`

#### It is used to extract a part of string from right side of given string. For example:-

```
SELECT RIGHT ('HY FAROOQ', '2');
```

### 14) `POSITION:-`

#### It is used to check the position of string from given string. For example:-

```
SELECT POSITION ('T' IN 'PAKISTAN');
```
