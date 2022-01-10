# Cluster vs Worker Threads

Here resides the examples that I provided on my blog article [Cluster vs Worker Threads](https://luk3skyw4lker-blog.vercel.app/posts/cluster-vs-worker-threads).

- cluster-example: http server with one cluster forked for each CPU of the machine (calculated dynamically using native Node.js modules);
- primes: the calculation of every prime number from 2 to 10,000,000 without the use of worker_threads
- primes_threads: the calculation of every prime number from 2 to 10,000,000 with the use of worker_threads

If there is any doubt, contact me on my email or open an issue on this repository. Thanks for reading my blog!
