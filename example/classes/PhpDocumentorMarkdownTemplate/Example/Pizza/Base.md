***

# Base

Represents a pizza base.



* Full name: `\PhpDocumentorMarkdownTemplate\Example\Pizza\Base`


## Constants

| Constant | Visibility | Type | Value |
|:---------|:-----------|:-----|:------|
|`YEAST_SOURDOUGH_STARTER`|private| |0b1|
|`YEAST_FRESH`|public| |0b10|
|`YEAST_ACTIVE_DRY`|public| |0b11|

## Properties


### sauce

The sauce used.

```php
protected \PhpDocumentorMarkdownTemplate\Example\Pizza\Sauce $sauce
```






***

### yeast

Type of yeast used.

```php
protected int $yeast
```






***

## Methods


### __construct



```php
public __construct(\PhpDocumentorMarkdownTemplate\Example\Pizza\Sauce $sauce, int $yeast = self::YEAST_SOURDOUGH_STARTER): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$sauce` | **\PhpDocumentorMarkdownTemplate\Example\Pizza\Sauce** |  |
| `$yeast` | **int** |  |




***

### getSauce



```php
public getSauce(): \PhpDocumentorMarkdownTemplate\Example\Pizza\Sauce
```











***

### getYeast



```php
public getYeast(): int
```











***


***
> Automatically generated from source code comments on 2022-04-24 using [phpDocumentor](http://www.phpdoc.org/) and [saggre/phpdocumentor-markdown](https://github.com/Saggre/phpDocumentor-markdown)
