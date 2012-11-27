# Unittest package for Sublime Text 2


By [Samuel Martin](http://blog.creaone.fr) <<martin.sam@gmail.com>>

Twitter: @[martinsam](http://twitter.com/martinsam)

## Demo
 @TODO

## Installation

### Automatic installation 

@TODO

### Manual installation 

#### MacOs
	cd /User/[Your User]/Library/Application\ Support/Sublime\ Text\ 2/Packages
	git clone https://github.com/martinsam/sublime-unittest ./Unittest

#### Linux
	cd /home/[Your user]/.config/sublime-text-2/Packages/
	git clone https://github.com/martinsam/sublime-unittest ./Unittest


## Snippet

### Assertions


snippet      |   method                                     | Checks that         | New in
-------------|----------------------------------------------|---------------------|------------ 
**asse**     |`assertEqual(first, second, msg=None)`        | a == b              |
**assne**    |`assertNotEqual(first, second, msg=None)`     | a != b              |
**asst**     |`assertTrue(expr, msg=None)`                  | bool(x) is True     |
**assf**     |`assertFalse(expr, msg=None)`                 | bool(x) is False    |
**assis**    |`assertIs(first, second, msg=None)`           | a is b              | 2.7
**assisnt**  |`assertIsNot(first, second, msg=None)`        | a is not b          | 2.7
**assisne**  |`assertIsNone (expr, msg=None)`               | x is None           | 2.7
**assisntne**|`assertIsNotNone(expr, msg=None)`             | x is not None       | 2.7
**assin**    |`assertIn(first, second, msg=None)`           | a in b              | 2.7
**assnin**   |`assertNotIn(first, second, msg=None)`        | a not in b          | 2.7
**assisins** |`assertIsInstance(obj, cls, msg=None)`        | isinstance(a, b)    | 2.7
**assnisins**|`assertNotIsInstance(obj, cls, msg=None)`     | not isinstance(a, b)| 2.7


It is also possible to check that exceptions and warnings are raised using the following methods:


snippet      |   method                                     | Checks that         | New in
-------------|----------------------------------------------|---------------------|------------ 
@todo        |||



There are also other methods used to perform more specific checks, such as:

snippet      |   method                                     | Checks that         | New in
-------------|----------------------------------------------|---------------------|------------ 
@todo        |||