---
title: isPlainObject
layout: post
---

## Description

isPlainObject is a function to check wether a val is a plain object.

## Syntax

> invincible.isPlainObject(val)

#### Params

Name | Type | Required | Default | Description
--- | --- | --- | ---
val | Any | true | | The source value to check

#### Return

Type | Description
--- | ---
Boolean | Return wether the value is a plain object

## Examples

``` js
invincible.isPlainObject({key: 'value'}) // true
invincible.isPlainObject([1, 2, 3]) // false
invincible.isPlainObject(new Test()) // false
```
