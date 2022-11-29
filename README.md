![1_-ttbjLpp9HMrpWdzSPckZQ](https://user-images.githubusercontent.com/28011628/204269417-e3068e15-e3f7-4cb1-9528-6df97f61ae25.png)



# DNA-Kmer-Speed-Test
DNA Kmer speed test in different languagues

In order to understand the background of this test, visit the original article here: https://towardsdatascience.com/how-fast-is-c-compared-to-python-978f18f474c7


### How to run the test

1. Clone the repository
2. Install the dependencies
3. Run `make LENGTH=11 -s` to run the test with kmer length 11
4. Or use `make LENGTH=13 LANGUAGES="go c cpp rust" -s` to run the test with kmer length 13 and only for the languages go, c, cpp and rust


### Kmer - Operation Amount

| Kmer | Generated |
|------|-----------|
| 11 | 4.194.304 |
| 12 | 16.777.216 |
| 13 | 67.108.864 |
| 14 | 268.435.456 |
| 15 | 1.073.741.824 |
| 16 | 4.294.967.296 |
| 17 | 17.179.869.184 |


# Test Results

### C

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.003s | Win11 / i9-12900KF |
| 12 | 0.012s | Win11 / i9-12900KF |
| 13 | 0.045s | Win11 / i9-12900KF |
| 14 | 0.187s | Win11 / i9-12900KF |
| 15 | 0.753s | Win11 / i9-12900KF |
| 16 | 3.017s | Win11 / i9-12900KF |
| 17 | 14.424s | Win11 / i9-12900KF |

### C++

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.003s | Win11 / i9-12900KF |
| 12 | 0.011s | Win11 / i9-12900KF |
| 13 | 0.063s | Win11 / i9-12900KF |
| 14 | 0.309s | Win11 / i9-12900KF |
| 15 | 1.100s | Win11 / i9-12900KF |
| 16 | 4.149s | Win11 / i9-12900KF |
| 17 | 16.361s | Win11 / i9-12900KF |

### Erlang

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.392s | Win11 / i9-12900KF |
| 12 | 1.664s | Win11 / i9-12900KF |
| 13 | 6.540s | Win11 / i9-12900KF |
| 14 | 25.941s | Win11 / i9-12900KF |
| 15 | 105.529s | Win11 / i9-12900KF |

### Go

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.014s | Win11 / i9-12900KF |
| 12 | 0.056s | Win11 / i9-12900KF |
| 13 | 0.219s | Win11 / i9-12900KF |
| 14 | 0.863s | Win11 / i9-12900KF |
| 15 | 3.553s | Win11 / i9-12900KF |
| 16 | 12.429s | Win11 / i9-12900KF |
| 17 | 49.861s | Win11 / i9-12900KF |

### Java

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.017s | Win11 / i9-12900KF |
| 12 | 0.052s | Win11 / i9-12900KF |
| 13 | 0.158s | Win11 / i9-12900KF |
| 14 | 0.599s | Win11 / i9-12900KF |
| 15 | 2.703s | Win11 / i9-12900KF |

### JavaScript

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.060s | Win11 / i9-12900KF |
| 12 | 0.230s | Win11 / i9-12900KF |
| 13 | 0.912s | Win11 / i9-12900KF |
| 14 | 3.607s | Win11 / i9-12900KF |
| 15 | 14.543s | Win11 / i9-12900KF |

### Perl

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.701s | Win11 / i9-12900KF |
| 12 | 2.734 | Win11 / i9-12900KF |
| 13 | 10.737s | Win11 / i9-12900KF |
| 14 | 46.343s | Win11 / i9-12900KF |
| 15 | 169.598s | Win11 / i9-12900KF |

### Python

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 2.271s | Win11 / i9-12900KF |
| 12 | 9.233s | Win11 / i9-12900KF |
| 13 | 36.638s | Win11 / i9-12900KF |
| 14 | 99.665s | Win11 / i9-12900KF |
| 15 | 414.169s | Win11 / i9-12900KF |

### Rust

| Kmer | Duration | (Optional) Runtime Env / OS |
|------|----------|-----------------------------|
| 11 | 0.012s | Win11 / i9-12900KF |
| 12 | 0.050s | Win11 / i9-12900KF |
| 13 | 0.202s | Win11 / i9-12900KF |
| 14 | 0.805s | Win11 / i9-12900KF |
| 15 | 3.322s | Win11 / i9-12900KF |
| 16 | 14.338s | Win11 / i9-12900KF |
| 17 | 54.414s | Win11 / i9-12900KF |



# Now it's your turn!

Participate in this public repository with your favourite language
