[TOC]

## RISC 计算机的主要问题是
1. the exploitation of instruction-level parallelism (initially through pipelining and later through multiple
instruction issue) 
2. the use of caches (initially in simple forms and later using more sophisticated organizations and optimizations).

ILP
DLP
TLP
RLP

## instructions set


## ILP
pipeline




数据相关

Loop: L.D      F0, 0(R2)
      ADD.D    F4, F0,F2
      S.D      F4, 0(R2)
      DADDIU   R2, R2, -8
      BNE      R2, R1, Loop 

