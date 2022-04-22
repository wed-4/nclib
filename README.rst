nclib
=====

nclibは、netcatをpythonで使えるようにしたライブラリです。

以下のような機能が実装されています。

- TCPおよびUDPソケットへの接続と待ち受けのための使いやすいインターフェース
- Pythonのストリームのようなオブジェクトを1つのインターフェイスで扱える機能
- より優れたソケットクラス、Netcatオブジェクト

  - Convenient receive methods for common socket usage patterns
  - Highly customizable logging
  - Interactive mode, connecting the socket to your stdin/stdout
  - Intelligent detection of socket closes and connection drops
  - Long-running functions cleanly abortable with ctrl-c
  - Lots of aliases in case you forget the right method name

- Mechanisms to launch processes with their in/out streams connected to sockets

  - Launch a process with gdb attached

- TCP and UDP server classes for writing simple python daemons
- A script to easily daemonize command-line programs

If you are familiar with pwntools, nclib provides much of the functionaly that
pwntools' socket wrappers do, but with the bonus feature of not being pwntools.

Installation
------------

.. code-block:: bash

    pip install nclib

Documentation
-------------

https://nclib.readthedocs.io/
