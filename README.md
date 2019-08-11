# RingBufferKotlin
Kotlin implementation of circular buffer, created for educational purposes.

Current implementation is not thread safe. It uses 2 pointers (read/write pos) and 2 boolean values (isFull/isEmpty). 
This allows to maintain full buffer capacity.
