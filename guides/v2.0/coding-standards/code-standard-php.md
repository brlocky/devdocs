---
layout: default
group: coding-standards
subgroup: Coding standards
title: PHP coding standard
menu_title: PHP coding standard
menu_order: 2
version: 2.0
github_link: coding-standards/code-standard-php.md
redirect_from: /guides/v1.0/coding-standards/code-standard-php.html
---

The Magento core development team uses the [Basic Coding Standard](http://www.php-fig.org/psr/psr-1/){:target="_blank"} and [Coding Style Guide](http://www.php-fig.org/psr/psr-2/){:target="_blank"}. Magento recommends that developers who create Magento extensions and customizations also use these standards.

Where possible, use [`PHP_CodeSniffer`](https://github.com/squizlabs/PHP_CodeSniffer){:target="_blank"} to automatically enforce these standards. Otherwise, standards and requirements must be applied through rigorous code review.

### Additional Standards

* Instead of a string literal, use PHP 5.5's `::class` keyword when referring to the fully qualified class name outside of that class. For example:

  ~~~
  $this->get(\Magento\Path\To\Class::class);
  ~~~