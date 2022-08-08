Copying a text file from source to destination using multi-threading concept.

In the given piece of code, a semaphore is created. A semaphore is nothing but a synchronization object that
allows limited degree of parallelism. It's simply a way to limit the number of consumers for a specific resource.

e.g. limiting the number of simultaneous calls to a database in an application.

A simple constructor is called for initialising threads with source and destination properties.

In the main() method, a start function is called which will take source & destination file names.

After providing number of threads as input, multithreading is initialised.
