# Multi-Threading-in-String-Similarity-Algorithm-
String matching is vital but slow for massive datasets like DNA. We multi-threaded the Rabin-Karp, KMP, and Boyer-Moore algorithms using data parallelism. Text is split into chunks with an m-1 character overlap to catch boundary matches. On the 3.34-billion-character human genome, our parallel Boyer-Moore hit a 12.18x speed-up on 16 threads.
