# HashTable Implementation in Python

I created this HashTable implementation working through the following article: https://realpython.com/python-hash-table/

The final version uses 'Closed Addressing' for dealing with Hash Collisions.
This means that the HashMap contains a list of buckets, that store a doubly-linked-list deque.

Optimally, every bucket contains only one Key-Value-Pair, but in case of hash collisions the Key-Value-Pair
with the same Hash as some other already existing Key-Value-Pair gets added to the deque.
