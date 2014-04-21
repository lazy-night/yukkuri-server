yukkuri server
==============

Raspberry Piのみで動きます。

.. code-block:: python

  $ pip install flask
  $ python app.py

127.0.0.1:5000で動き出す。

使用方法
--------

http://127.0.0.1:5000/yukkuri/<word>

http://127.0.0.1:5000/yukkuri/api/<word>

http://127.0.0.1:5000/syaberu/<word>

そのページでゆっくりボイスを聞くか、jsonデータを得るか、Raspberry Piをしゃべれせることができます。

ゆっくりボイスはこちらにあるものを使用しています。

`AquesTalk Pi - Raspberry Pi用の音声合成 <http://www.a-quest.com/products/aquestalkpi.html>`_
