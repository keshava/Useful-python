* The short way - MD5 hash, take first 6 char as key for hash table lookup, if there is a collision, just increment the hash by 1.
* The long way - String mapping Algorithm to map long strings to short strings (Base 62) - https://impythonist.wordpress.com/2015/10/31/building-your-own-url-shortening-service-with-python-and-flask/