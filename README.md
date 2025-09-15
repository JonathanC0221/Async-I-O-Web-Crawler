# Async-I-O-Web-Crawler

A single-threaded web crawler that uses asynchronous I/O and the cURL multi-interface to maintain multiple simultaneous connections within the same thread. Starting from a seed URL, it searches for up to 50 valid PNG URLs (or a user-specified number) and logs them into log.txt. This approach enables concurrent transfers without using pthreads, demonstrating efficient network programming and non-blocking I/O techniques.
