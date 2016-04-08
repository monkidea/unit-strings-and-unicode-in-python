# Strings and Unicode in Python

Dealing with text starts like an easy task. You can create text/string literals, read and write them to disc, and show them to your user with a simple `print` statement. But once you are past the simple tasks and you need to start working with advanced use cases, strings and text handling in general quickly become a complicated subject 😨.

Without doubt, the biggest compatibility issue introduced with Python 3 was the Unicode support. Python 3 introduced a new data type `bytes` which is equivalent of Python 2' `str` and the replaced Python 2's `unicode` with `str`. So Python 2's `unicode` is Python 3's `str` and Python 2's `str` is Python 3's `bytes`. 😦😕😖 Confusing, uh? 😩. That's why this guide will take into account the differences between Python 2 and Python 3. We'll make explicit notes on different versions.

Before we can jump to explain unicode and strings we need to first understand how text handling works in our computers. That's the subject of our next lesson.
