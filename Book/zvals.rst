Zvals
=====

..
    Writing this I'm assuming that in the previous chapter basic extension syntax was introduced und people know how to
    define a function without arginfo or zpp. So this chapter can have PHP_FUNCTION examples, just without heavy zpp
    usage

In this chapter the "zval" data structure, which is used to represent PHP values, is introduced. We explain the concepts
behind zvals and how to use them in extension code.
这一单元主要介绍"zval"结构类型，"zval"结构用来代表PHP变量，在本单元中

内容:

.. toctree::
    :maxdepth: 2

    zvals/basic_structure.rst
    zvals/memory_management.rst
    zvals/casts_and_operations.rst