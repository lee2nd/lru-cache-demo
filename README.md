# lru-cache-demo

1. Caching can improve the performance of Python code, especially for functions that are called multiple times with the same arguments
2. This can significantly improve the performance of "recursive functions" and "functions that call external resources", such as databases or APIs.
3. When to use LRU cache:
   * For expensive or I/O-bound functions
   * To improve the performance of recursive functions
4. Reference
   * https://docs.python.org/3/library/functools.html
   * https://medium.com/@jepersyne/python-functools-lru-cache-d5cb632df710
   * https://www.linkedin.com/feed/update/urn:li:activity:7122248409431818240?utm_source=share&utm_medium=member_desktop
