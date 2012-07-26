Git
==========

ユーザ環境初期設定
=====================

.. code-block:: bash

    $ git config --global user.name "User Name"
    $ git config --global user.email "User Email"
    $ git config --global color.ui auto


CUIコミットのエディタ変更
============================

環境変数の $GIT_EDITOR を参照しているらしい。無ければ $EDITOR
一時的に設定するなら以下のように入力。

.. code-block:: bash

    $ export GIT_EDITOR=vi

当然、自動で設定されるようにするには .bashrc 辺りに設定が必要

