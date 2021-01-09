Multiparty-Computation-Papers
=========================================
MPC or SMPC related papers that are a must read
---

## A. Secret Sharing
### 1. [How to share a secret](papers/s79.pdf)
Shamir's secret sharing scheme

### 2. [short secret](papers/secretshort.pdf)
Reducing the share space to s/|m| to  make things more efficient.

### 3. [Chor VSS] (papers/chodVSS.pdf)
This paper introduces two notions - verifyable secret sharing and simulatneous broadcast.

## B. Byzantine Agreement
### 1. []()

## C. Garbled Circuits
###

## D. Oblivious transfer
###

## E. Adversary
###

## F. Theoritical
### 1. [How to play any game - GMW protocol](papers/gmw87.pdf)
Provides completeness theorem for honest majority

## G. Communication complexity
### 1. [communication required for unconditionally secure mult] (papers/unconditionally_secure_multiplication.pdf)
shows any information theoretic protocol that follows gate by gate design must communicate for every multiplication gate (in both honest and semi honest) and both honest and dishonest majority with preprocessing where secret sharing scheme is additive.

## H. General
### 1. [MPC overview] (papers/Lin20.pdf)
Presents an overview of MPC for beginners, nothing too deep, but does have cite some important papers that newbies can use to get started.

## I. Application
### 1. [Satellite collision](papers/satellitempc.pdf)
Presents a circuit for computing probability of computing satellite collision using GMW protocol

## J. Rationality
### 1. [Rationality and secret sharing] (papers/halpern_STOC04.pdf)
Halpern et al present their thoughts on the rationality of a party in secret sharing scheme. It is rational to cheat in such a scheme, but cooperation can be enforced by keeping it uncertain if the protocol ends after the current round or not. If it doesn't end, and cheating is detected then the protocol is restarted without cheating parties.

### 2. [Rationality and Adversarial behavior in MPC] (papers/lysyanskaya2006.pdf)
Authors split parties into 3 categories - Rational, adversarial, selfish or irrational. This is called the mixed behavior model, and the authors define a class of functions that can be computed in this model. Utilizes idea of [J.1].
