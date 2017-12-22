DQN-in-the-Caffe
================

DQN-in-the-Caffe is an implementation of Deep Q-Network using Caffe.

Requirements
--

- Caffe (with two pull requests and minor fixes on them)
 - https://github.com/BVLC/caffe/pull/1228 for step execution of solving
 - https://github.com/BVLC/caffe/pull/1122 for AdaDelta solver
 - At the moment my forked repository's dqn branch https://github.com/muupan/caffe/tree/dqn can be used with DQN-in-the-Caffe
- Arcade Learning Environment
- etc.

Algorithm Details
--

See http://www.cs.toronto.edu/~vmnih/docs/dqn.pdf for the details of DQN.

Demo
--

https://www.youtube.com/watch?v=p88R2_3yWPA


---
- [install reference](http://blog.csdn.net/hmxiaobao/article/details/51275122)
- [ALE](http://www.arcadelearningenvironment.org/)
- [Oringinal repo](https://github.com/muupan/dqn-in-the-caffe)
### Change some code in dqn.cpp & dqn.hpp and CMakeLists.txt:
  #ifdef USE_OPENCV
  #endif  // USE_OPENCV
  
  
