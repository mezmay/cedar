血脂肪過高
=====

.. _dislipidemia:

什麼叫做血脂異常？
-----------
包括下列指數異常：

* 總膽固醇
* 高密度脂蛋白
* 低密度脂蛋白
* 三酸甘油脂

什麼原因造成血脂異常？
----------------

* 飲食
* 遺傳
* 代謝症候群
* 其他因素

不吃藥的情況，如何改善生活習慣以降低血脂？
--------------------------------




To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

