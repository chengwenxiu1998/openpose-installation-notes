本来tensorfolw是2.*版本，缺module（tensorflow.contrib），百度说是2.0以后被遗弃了，所以开始尝试低版本……

ERROR: Could not find a version that satisfies the requirement tensorflow==1.6.0 (from versions: 1.13.0rc1, 1.13.0rc2, 1.13.1, 1.13.2, 1.14.0rc0, 1.14.0rc1, 1.14.0, 1.15.0rc0, 1.15.0rc1, 1.15.0rc2, 1.15.0rc3, 1.15.0, 1.15.2, 1.15.3, 2.0.0a0, 2.0.0b0, 2.0.0b1, 2.0.0rc0, 2.0.0rc1, 2.0.0rc2, 2.0.0, 2.0.1, 2.0.2, 2.1.0rc0, 2.1.0rc1, 2.1.0rc2, 2.1.0, 2.1.1, 2.2.0rc0, 2.2.0rc1, 2.2.0rc2, 2.2.0rc3, 2.2.0rc4, 2.2.0, 2.3.0rc0, 2.3.0rc1, 2.3.0rc2, 2.3.0)
ERROR: No matching distribution found for tensorflow==1.6.0

```python
/**
本次测试Keras版本
Keras                              1.0.8
Keras-Applications                 1.0.8
Keras-Preprocessing                1.1.0
**/
```

**1.13.0rc1**

ImportError: cannot import name '**keras_export**' from 'tensorflow.python.util.tf_export' (D:\anaconda\lib\site-packages\tensorflow\python\util\tf_export.py)

**1.13.0rc2**

ImportError: cannot import name '**keras_export**' from 'tensorflow.python.util.tf_export' (D:\anaconda\lib\site-packages\tensorflow\python\util\tf_export.py)

**1.13.1**

ImportError: cannot import name '**keras_export**' from 'tensorflow.python.util.tf_export' (D:\anaconda\lib\site-packages\tensorflow\python\util\tf_export.py)

**1.13.2**

ImportError: cannot import name '**keras_export**' from 'tensorflow.python.util.tf_export' (D:\anaconda\lib\site-packages\tensorflow\python\util\tf_export.py)

**1.14.0rc0**

ImportError: cannot import name '**export_saved_model**' from 'tensorflow.python.keras.saving.saved_model' (D:\anaconda\lib\site-packages\tensorflow\python\keras\saving\saved_model\__init__.py)

**1.14.0rc1**

ImportError: cannot import name '**export_saved_model**' from 'tensorflow.python.keras.saving.saved_model' (D:\anaconda\lib\site-packages\tensorflow\python\keras\saving\saved_model\__init__.py)

**1.14.0**

ImportError: cannot import name '**export_saved_model**' from 'tensorflow.python.keras.saving.saved_model' (D:\anaconda\lib\site-packages\tensorflow\python\keras\saving\saved_model\__init__.py)

**1.15.0rc0**

2020-07-29 21:48:54.671070: W tensorflow/stream_executor/platform/default/dso_loader.cc:55] Could not load dynamic library 'cudart64_100.dll'; dlerror: cudart64_100.dll not found
2020-07-29 21:48:54.681502: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
Traceback (most recent call last):
  File "run.py", line 6, in <module>
    from tf_pose import common
  File "E:\B\tf-pose-estimation\tf_pose\__init__.py", line 5, in <module>
    from tf_pose.runner import infer, Estimator, get_estimator
  File "E:\B\tf-pose-estimation\tf_pose\runner.py", line 8, in <module>
    from tf_pose import eval
  File "E:\B\tf-pose-estimation\tf_pose\eval.py", line 13, in <module>
    from tf_pose.estimator import TfPoseEstimator
  File "E:\B\tf-pose-estimation\tf_pose\estimator.py", line 14, in <module>
    import tensorflow.contrib.tensorrt as trt
ModuleNotFoundError: No module named '**tensorflow.contrib.tensorrt**'

**1.15.0rc1**

ModuleNotFoundError: No module named '**tensorflow.contrib.tensorrt**'

**1.15.0rc2**

ModuleNotFoundError: No module named '**tensorflow.contrib.tensorrt**'

**1.15.0rc3**

ModuleNotFoundError: No module named '**tensorflow.contrib.tensorrt**'

**1.15.0**



**1.15.2**

**1.15.3**

**2.0.0a0**

**2.0.0b0**

**2.0.0b1**

**2.0.0rc0**

**2.0.0rc1**

**2.0.0rc2**

**2.0.0**

**2.0.1**

**2.0.2**

**2.1.0rc0**

**2.1.0rc1**

**2.1.0rc2**

**2.1.0**

**2.1.1**

**2.2.0rc0**

**2.2.0rc1**

**2.2.0rc2**

**2.2.0rc3**

**2.2.0rc4**

**2.2.0**

**2.3.0rc0**

**2.3.0rc1**

**2.3.0rc2**

**2.3.0**




