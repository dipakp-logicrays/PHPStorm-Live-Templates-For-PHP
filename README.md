# PHP Awesome Snippets - PhpStorm Live Templates
Live Templates for PhpStorm (PHP)

## Usage
Type a snippet (or part of it), press `Enter` or `Tab` or `CTRL+SPACE` and the snippet will expand just right there.

These snippets or Live Templates work in **PHP context**.

## How to install
1) Download and copy the *PHP Awesome Snippets.xml* file to your templates folder:

* Linux: `~/.config<product name><version number>\config\templates`

e.g. `~/.config/JetBrains/PhpStorm2023.3/templates` on Linux PhpStorm 2023

2) Restart PhpStorm.

*Notes*: 
- Above Installation steps is for Linux Plateform, Also I have installed PHPStorm using snap.
- If you are on `Windows` or `Mac`, then templates path directories are changed.

----
### PHP tags

| Snippet | Output |
| --- | --- |
| php | `<?php ...?>` |
| po | `<?php...` |
| pc | `?>` |
| peco | `<?= ... ?>` |

----
### Classes, interfaces and traits

| Snippet | Output |
| --- | --- |
| cl | `class ClassName {...}` |
| cli | `class ClassName implements Interfaces {...}` |
| in | `interface InterfaceName {...}` |
| trt | `trait TraitName {...}` |

***Tip :*** You can call `Class` snippets above with `abstract` or `final` form by using below 2 commands.
> * `acl` for `abstract class ClassName {...}`
> * `fcli` for `final class ClassName implements Interfaces {...}`

----
### Constructor

| Snippet | Output |
| --- | --- |
| pubc | `public function __construct(Type $args) {...}` |
| proc | `protected function __construct(Type $args) {...}` |
| pric | `private function __construct(Type $args) {...}` |

----
### Control structures

| Snippet | Output |
| --- | --- |
| ifb | `if (condition) {...}` |
| ifel | `if (condition) {...} else {...}` |
| ifelif | `if (condition) {...} elseif (condition) {...} else {...}` |
| sw | `switch ($variable) { case 'label': ... break; ... default: ... break; }` |
| tern | `condition ? if_true : if_false;` |

***Tip :*** Other `if ... else` form is also available if needed:
 
> | Snippet | Output |
> | --- | --- |
> | ifen | `if (condition): ... endif;` |
> | ifelen | `if (condition): ... else: ... endif;` |
> | ifelifen | `if (condition): ... elseif (condition): ... else: ... endif;` |

----
### Loops structures

| Snippet | Output |
| --- | --- |
| foren | `foreach ($iterable as $item): {...} endforeach;` |
| forenk | `foreach ($iterable as $key => $item): {...} endforeach;` |
| forl | `for ($i = 0; $i < $limit; $i++) {...}` |
| forlen | `for ($i = 0; $i < $limit; $i++): {...} endfor;` |

----
### Superglobals

| Snippet | Output |
| --- | --- |
| gget | `$_GET["..."]` |
| gpost | `$_POST["..."]` |
| gss | `$_SESSION["..."]` |
| gfile | `$_FILES['...']['...']` |
| gcook | `$_COOKIE["..."]` |
| gser | `$_SERVER["..."]` |
| greq | `$_REQUEST["..."]` |
| genv | `$_ENV["..."]` |
| gglob | `$GLOBALS["..."]` |

----
### Arrays

| Snippet | Output |
| --- | --- |
| ark | `['key' => value, 'key' => value,...]` |

* Addon snippet : use with `ark` snippet to add `value` or `key => value` if needed.

----
### Common functions calls

| Snippet | Output |
| --- | --- |
| df | `define("...", "...");` |
