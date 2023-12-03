# OpenACC Training Series
OpenACC Training Resources provided by OpenACC.org & NERSC Tutorials

# Contents
Nvidia Architecuture : 202312_IBS_Lect1-nvidia-arch.pdf

OpenACC : 202312_IBS_Lect2-openacc.pdf

Parallel Computational Sciences :202312_IBS_Lect3-parallel-cfd.pdf

# test00.f90 
tesf00.f90은 nvfortran 또는 pgfortran 컴파일러 점검을 위하여 만들었습니다. 간단한 pi를 Monte Carlo 방식으로 계산하는 프로그램입니다. 

test00.f90 : computing pi = int [ 1/(1+x^2) ] dx = arctan(x) + c 

                       tan(pi/4) = 1 --> arctan(1) = pi / 4
                       
                       int from a to b [ f(x) ] dx = 1/N * sum[ f(x_k) ] from 1 to N

                       
