# Jellygnite Admin Toggle Checkbox

## Introduction

Converts a checkbox to a toggle slider.


## Installation

```
composer require jellygnite/silverstripe-admin-toggle-checkbox
```

## Usage

Simply add the class 'toggle' to your CheckboxField. e.g.

```
CheckboxField::create('IsFeatured', 'Is Featured?')->addExtraClass('toggle'),
```


Based on https://github.com/i-lateral/silverstripe-admin-toggle-checkbox