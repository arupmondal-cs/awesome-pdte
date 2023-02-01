# awesome Secure Comparison and Private Decision Tree Evaluation [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

The idea of creating this awesome reading list is initited and inspired by [Abdelrahaman Aly](https://scholar.google.es/citations?user=FDfDueMAAAAJ&hl=en) for our [TII](https://www.tii.ae/) projects, and the list format was insipired from [awesome-mpc](https://github.com/rdragos/awesome-mpc). It is designed to have a central place where everyone can find important materials to the topic of **secure comparison (SC)** and **private decision tree evaluaton (PDTE)**.

Moreover, the list is sorted by publishing year.

Please feel free to do a pull request with any **SC** and **PDTE** resource you know and it is not on the list. The current classification might not be most suitable one and I am open to any suggestions.

---

## Contents

- [Secure Comparison](#secure-comparison)
- [Private Decision Tree Evaluation](#private-decision-tree-evaluation)

---


## Secure Comparison

- [Through the Looking-Glass: Benchmarking Secure Multi-Party Computation Comparisons for ReLU's](https://eprint.iacr.org/2022/202) [CANS 2022] - This paper present a series of constant round variations and adaptations of the secure comparison protocols, introduced by [2021/119](https://eprint.iacr.org/2021/119).
- [A Method for Securely Comparing Integers using Binary Trees](https://eprint.iacr.org/2021/1646) [ePrint 2021/1646] - This paper proposed a new protocol for secure integer comparison which consists of parties having each a private integer. Their protocol relies on binary decision trees that is a special case of branching programs and can be implemented using homomorphic encryption.
- [Rabbit: Efficient Comparison for Secure Multi-Party Computation](https://eprint.iacr.org/2021/119) [FC 2021] - This work presents a novel construction for general *n*-party private comparison, secure against an active adversary, in the dishonest majority setting. 
- [Improved Primitives for Secure Multiparty Integer Computation](https://link.springer.com/chapter/10.1007/978-3-642-15317-4_13) [SCN 2010] - This paper presents a bunch of multiparty computation protocols such as integer truncation and comparison, that provide core operations for secure integer and fixed-point computation. 
- [Homomorphic encryption and secure comparison](https://dl.acm.org/doi/10.1504/IJACT.2008.017048) [International Journal of Applied Cryptography 2008] - This paper proposed a protocol for secure comparison of integers based on homomorphic encryption, and also proposed a homomorphic encryption scheme that can be used in their comparison protocol, makes it more efficient than previous solutions, and can also be used as the basis of efficient and general secure multiparty computation.


## Private Decision Tree Evaluation

- [Scalable Private Decision Tree Evaluation with Sublinear Communication](https://dl.acm.org/doi/10.1145/3488932.3517413) [AsiaCCS 2022] - This paper  proposeed two sublinear-communication private decision tree evaluation protocols by carefully combining a modified tree encoding method, the Shared Oblivious Selection functionality and efficient secure computation techniques.
- [SortingHat: Efficient Private Decision Tree Evaluation via Homomorphic Encryption and Transciphering](https://eprint.iacr.org/2022/757) [ACM CCS 2022] - This paper present an efficient non-interactive design of private decision tree evaluation technique based on fully-homomorphic encryption. Also, as part of their protocol design, they proposed a fast homomorphic comparison.
- [Private Decision Tree Evaluation with Constant Rounds via (Only) SS-3PC over Ring
](https://dl.acm.org/doi/abs/10.1007/978-3-030-62576-4_15) [ProvSec 2020] - This papers 
- [Private Evaluation of Decision Trees using Sublinear Cost](https://petsymposium.org/popets/2019/popets-2019-0015.php) [PETS 2019]
- [Privately Evaluating Decision Trees and Random Forests](https://eprint.iacr.org/2015/386) [PETS 2016]

### SoK
- [SoK: Modular and Efficient Private Decision Tree Evaluation](https://eprint.iacr.org/2018/1099) [PoPETs 2019]
- 
