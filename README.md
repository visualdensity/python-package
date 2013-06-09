Python Modules Example
======================

Sample package to shows the structure typical pyhon package. It answers 
questions like how do one create subpackages, what is the `__init__.py` 
is used for and what is supposed to be in the `__init__.py` file. 

This package works, just that it does not do much. To give it a run, try 
the following:

    from mainpackage import *

    main_package = Top_class()
    main_package.test_me()

    sub_package1 = Sub1_class()
    sub_package.test_me()

    sub_package2 = Sub2_class()
    sub_package.test_me()


Resources
---------

  * http://docs.python.org/2/tutorial/modules.html#packages
  * http://mikegrouchy.com/blog/2012/05/be-pythonic-__init__py.html
