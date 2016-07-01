# multiset
multiset combinations of k out of n (n multichoose k)

This repository contains a Java implementation of the multiset generators. Implementations for other languages can be found at https://github.com/ekg/multichoose


## Overview

This library implements an efficient loopless multiset combination generation algorithm which is (approximately) described in "Loopless algorithms for generating permutations, combinations, and other combinatorial configurations." G Ehrlich - Journal of the ACM (JACM), 1973. (Algorithm 7.)

The method generates all multisets that would be generated from taking k elements from a multiset of n. Repeated multisets are possible if the input set contains repeated elements. The number of multiset combinations equals the multinomial coefficient (n multichoose k).
