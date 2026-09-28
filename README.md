# Parallel and Distributed Computing

OPIT COMP-5002 · Professor Sylvester Kaczmarek

Practical materials for the course. Each laboratory is self-contained and focuses on a different parallel or distributed computing model. Read the laboratory README before running its commands.

## Course laboratories

| Week | Activity | Repository |
|---|---|---|
| 2 | LAB1 | [Threading, race conditions and locks](https://github.com/OPIT-CS/comp5002-lab1-threading-locks) |
| 3 | LAB2 | [Bounded buffer and synchronization](https://github.com/OPIT-CS/comp5002-lab2-bounded-buffer) |
| 4 | LAB3 | [Multiprocessing and process pools](https://github.com/OPIT-CS/comp5002-lab3-process-pool) |
| 6 | LAB4 | [MPI collective communication](https://github.com/OPIT-CS/comp5002-lab4-mpi-collectives) |
| 11 | LAB5 | [Distributed data processing with Dask](https://github.com/OPIT-CS/comp5002-lab5-distributed-frameworks) |

The GitHub laboratories are practical course activities. Official assessments, discussions, submission dates and grades remain in Canvas.

## Using the repositories

Use the assignment repository provided through GitHub Classroom for your work. The shared repositories above contain the course starters and instructions; do not submit work into the shared repositories or publish completed answers publicly.

Follow the setup and execution instructions in each laboratory README. Some starter code is intentionally incomplete until the required tasks are implemented.

The laboratories progress from shared-memory concurrency and synchronization, through multiprocessing and distributed-memory MPI, to a higher-level distributed data-processing framework.

## Course coverage

The practical sequence reinforces:

- Python threads, race conditions, locks and the GIL
- condition variables and producer-consumer synchronization
- process-based parallelism and process pools
- distributed-memory programming with MPI collectives
- partitioned data processing and lazy execution with Dask
