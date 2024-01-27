體重管理
=====

.. _installation:

身體質量指數（BMI）：
-----------------



.. math::  BMI = \frac{體重(公斤)}{身高(公尺)^2} 


體重是否正常的判斷：
------------------

根據國民健康署，體重正常與否可分類為下列幾種：

* 體重過輕：BMI<18.5
* 體重正常：18.5<=BMI<24
* 體重過重：24<=BMI<27
* 輕度肥胖：27<=BMI<30.0
* 中度肥胖：30.0<=BMI<35
* 重度肥胖：BMI>=35

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:
