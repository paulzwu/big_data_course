..  _lesson3_4:

=================================
Day 3 (4): Code and Bash Example
=================================

Mapper
======

.. literalinclude:: ../python_code/map_reduce/mapper.py
   :language: python
   :linenos:

``cat ../data/hadoop_words.txt | python mapper.py``

.. literalinclude:: ../python_code/map_reduce/reducer.py
   :language: python
   :linenos:


``cat ../data/hadoop_words.txt | ./mapper.py | sort |./reducer.py``

Questions
=========

1. Why do I need the sort command when I run this locally?
2. Why do I *not* need to sort when running on Hadoop?
