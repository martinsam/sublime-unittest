# Unittest package for Sublime Text 2


By [Samuel Martin](http://blog.creaone.fr) <<martin.sam@gmail.com>>

Twitter: @[martinsam](http://twitter.com/martinsam)

## Demo
 @TODO

## Installation

### Automatic installation 

@TODO - http://wbond.net/sublime_packages/package_control

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

	assertRaises(exc, fun, *args, **kwds)
	assertRaisesRegexp(exc, re, fun, *args, **kwds)

There are also other methods used to perform more specific checks, such as:

snippet      |   method                                                               | Checks that         | New in
-------------|------------------------------------------------------------------------|---------------------|------------ 
**assae**    | `assertAlmostEqual(first, second, places=7, msg=None, delta=None)`     |                     |
**assnae**   | `assertNotAlmostEqual(first, second, places=7, msg=None, delta=None)`  |                     |
**assg**     | `assertGreater(first, second, msg=None)`                               |                     | 2.7
**assge**    | `assertGreaterEqual(first, second, msg=None)`                          |                     | 2.7
**assl**     | `assertLess(first, second, msg=None)`                                  |                     | 2.7
**assle**    | `assertLessEqual(first, second, msg=None)`                             |                     | 2.7
**assrm**    | `assertRegexpMatches(text, regexp, msg=None)`                          |                     | 2.7
**assnrm**   | `assertNotRegexpMatches(text, regexp, msg=None)`                       |                     | 2.7
**assie**    | `assertItemsEqual(actual, expected, msg=None)`                         |                     | 2.7
**assdcs**   | `assertDictContainsSubset(expected, actual, msg=None)`                 |                     | 2.7
 	 