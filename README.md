# Herb Sutter's Effective Concurrency Column Archive

If you search the web for articles about low-level concurrency, you're bound to come across references to [Herb Sutter](https://herbsutter.com/)'s *Effective Concurrency* column.
Published between 2007 and 2010 in *Dr. Dobb's Journal*, these articles focused on building a consistent mental model for reasoning about concurrency.

Now that *Dr. Dobb's Journal* has [been closed](https://news.ycombinator.com/item?id=8758915), those articles have effectively been lost.   
Even the Internet Archive's Wayback Machine seems to have only archived [the first page of each article](https://web.archive.org/web/20110528165735/http://www.drdobbs.com/go-parallel/article/showArticle.jhtml?articleID=227500074). While they may no longer be fully up to date, I believe they're still valuable.

This repo is my attempt to find and archive those articles.


## List

Note that the quality varies, ranging from [okay](./src/2008_11_Dr_Dobbs_Journal.pdf) to [great](./src/2010_08_Dr_Dobbs.pdf).

Currently missing (3/33): No 19, No 29 and No 30.


| No      | Name                                                                                                       |
|---------|------------------------------------------------------------------------------------------------------------|
| EC #1   | [The Pillars of Concurrency](./src/2007_08_Dr_Dobbs_Journal.pdf)                                           |
| EC #2   | [How Much Scalability Do You Have or Need?](./src/2007_09_Dr_Dobbs_Journal.pdf)                            |
| EC #3   | [Use Critical Sections (Preferably Locks) to Eliminate Races](./src/2007_10_Dr_Dobbs_Journal.pdf)          |
| EC #4   | [Apply Critical Sections Consistently](./src/2007_11_Dr_Dobbs_Journal.pdf)                                 |
| EC #5   | [Avoid Calling Unknown Code While Inside a Critical Section](./src/2007_12_Dr_Dobbs_Journal.pdf)           |
| EC #6   | [Use Lock Hierarchies to Avoid Deadlock](./src/2008_01_Dr_Dobbs_Journal.pdf)                               |
| EC #7   | [Break Amdahl's Law!](./src/2008_02_Dr_Dobbs_Journal.pdf)                                                  |
| EC #8   | [Going Superlinear](./src/2008_03_Dr_Dobbs_Journal.pdf)                                                    |
| EC #9   | [Super Linearity and the Bigger Machine](./src/2008_04_Dr_Dobbs_Journal.pdf)                               |
| EC #10  | [Interrupt Politely](./src/2008_05_Dr_Dobbs_Journal.pdf)                                                   |
| EC #11  | [Maximize Locality, Minimize Contention](./src/2008_06_Dr_Dobbs_Journal.pdf)                               |
| EC #12  | [Choose Concurrency-Friendly Data Structures](./src/2008_07_Dr_Dobbs_Journal.pdf)                          |
| EC #13  | [The Many Faces of Deadlock](./src/2008_08_Dr_Dobbs_Journal.pdf)                                           |
| EC #14  | [Lock-Free Code: A False Sense of Security](./src/2008_09_Dr_Dobbs_Journal.pdf)                            |
| EC #15  | [Writing Lock-Free Code: A Corrected Queue](./src/2008_10_Dr_Dobbs_Journal.pdf)                            |
| EC #16  | [Writing a Generalized Concurrent Queue](./src/2008_11_Dr_Dobbs_Journal.pdf)                               |
| EC #17  | [Understanding Parallel Performance](./src/2008_12_Dr_Dobbs_Journal.pdf)                                   |
| EC #18  | [Measuring Parallel Performance: Optimizing a Concurrent Queue](./src/2009_01_Dr_Dobbs_ournal.pdf)         |
| EC #19  | volatile vs. volatile                                                                                      |
| EC #20  | [Sharing Is the Root of All Contention](./src/2009_02_Dr_Dobbs_Digest.pdf)                                 |
| EC #21  | [Use Threads Correctly = Isolation + Asynchronous Messages](./src/2009_03_Dr_Dobbs_Digest.pdf)             |
| EC #22  | [Use Thread Pools Correctly: Keep Tasks Short and Nonblocking](./src/2009_04_Dr_Dobbs_Digest.pdf)          |
| EC #23  | [Eliminate False Sharing](./src/2009_05_Dr_Dobbs_Digest.pdf)                                               |
| EC #24  | [Break Up and Interleave Work to Keep Threads Responsive](./src/2009_06_Dr_Dobbs_Digest.pdf)               |
| EC #25  | [The Power of "In Progress"](./src/2009_07_Dr_Dobbs_Digest.pdf)                                            |
| EC #26  | [Design for Manycore Systems](./src/2009_08_Dr_Dobbs_Digest.pdf)                                           |
| EC #27  | [Avoid Exposing Concurrency – Hide It Inside Synchronous Methods](./src/2009_10_Dr_Dobbs_Digest.pdf)       |
| EC #28  | [Prefer Structured Lifetimes - Local, Nested, Bounded, Deterministic](./src/2009_11_Dr_Dobbs_Digest.pdf)   |
| EC #29  | Prefer Futures to Baked-In "Async APIs"                                                                    |
| EC #30  | Associate Mutexes with Data to Prevent Races                                                               |
| EC #31  | [Prefer Using Active Objects Instead of Naked Threads](./src/2010_06_Dr_Dobbs.pdf)                         |
| EC #32  | [Prefer Using Futures or Callbacks to Communicate Asynchronous Results](./src/2010_08_Dr_Dobbs.pdf)        |
| EC #33  | [Know When to Use an Active Object Instead of a Mutex](./src/2010_09_Dr_Dobbs.pdf)                         |


## Thanks

Thanks to [Jacob Filipp](https://jacobfilipp.com/DrDobbs) for hosting the Dr. Dobbs DVD (most of the pdf comes from there).

Thanks to [Miro Samek]( https://www.state-machine.com/) for No 31 and No 33.

Thanks to [Pete Shearer](https://www.peteonsoftwares.com) for No 32.

Thanks to [Herb Sutter](https://herbsutter.com/) for writing those articles.

## Copyright 

This is an archiving project. I do not own any of those articles.

If you are Herb Sutter and you want this repo to be modified or deleted, please reach out.
