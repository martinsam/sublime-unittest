# Unittest package for Sublime Text 2


By [Samuel Martin](http://blog.creaone.fr) <<martin.sam@gmail.com>>

Twitter: @[martinsam](http://twitter.com/martinsam)

## Installation

	cd /User/[Your User]/Library/Application\ Support/Sublime\ Text\ 2/Packages
	git clone https://github.com/martinsam/sublime-unittest ./Unittest

## Snippet

### Assertions


snippet     |   method                                     | Checks that
------------|----------------------------------------------|-------
**asse**    |`assertEqual(first, second, msg=None)`        | a == b
**assne**   |`assertNotEqual(first, second, msg=None)`     | a != b
**asst**    |`assertTrue(expr, msg=None)`                  | bool(x) is True
**assf**    |`assertFalse(expr, msg=None)`                 | bool(x) is False
**assis**   |`assertIs(first, second, msg=None)`           | a is b
            |`assertIsNot(first, second, msg=None)`        | a is not b
            |`assertIsNone (expr, msg=None)`               | x is None
            |`assertIsNotNone(expr, msg=None)`             | x is not None
            |`assertIn(first, second, msg=None)`           | a in b
            |`assertNotIn(first, second, msg=None)`        | a not in b
            |`assertIsInstance(obj, cls, msg=None)`        | isinstance(a, b)
            |`assertNotIsInstance(obj, cls, msg=None)`     | not isinstance(a, b)


