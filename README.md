# GROUP-NAME - DOBBY - lab 3 - variant 5

- We define a class named SDFGraph and a class named Node.
The former class is used to define a Synchronous Data Flow(SDF) class.
The latter class is used to define a Node class 
contain its input and output token and its function.
Its initialization name means the node's name,

- Secondly, we add all nodes to nodes list and  put the output token and input token into queue.
They are used to calculate the solution of quadratic formula.

- Thirdly, we traverse all nodes in list nodes, we calculate the function effected it and we also record their input and output,then we put them into a queue so that the relationship between nodes are recorded.

## Project structure

- `SDFGraph.py` -- Implementation the class of `SDFGraph` and `Node`.

- `SDFGraph_test.py` -- Unit PBT tests for `SDFGraph.py`.

## Contribution

- Du,Mei(212320038@hdu.edu.cn) -- Implement `SDFGraph.py`.
- zhuhaonan(921057454@qq.com) -- Implement `SDFGraph_test.py`.

## Changelog

- 16.06.2022 - 2

  - Implement `SDFGraph.py` and `SDFGraph_test.py`.
  - Github check and fix.
  - update README.

## Design notes

- The synchronous dataﬂow is achieved through the tokens.
- And we can design an input language for building computational process description;
- We can design interpreter, 
- which allows library user to execute a computational process description;
- We can achieve an interpreter for computational process models.
