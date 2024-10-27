# CPP-Style-Guide
C++ Style Guide

Variable Initialization:

Use = whenever you can.
Use initializer-list syntax {} only for element initializers (of containers and aggregates).
Use function-call syntax () to call a constructor, viewed as an object-factory.

int i {0};
std::vector<int> v {1, 2, 3, 4};
auto w = Widget(name, price, quantity);

https://quuxplusone.github.io/blog/2019/02/18/knightmare-of-initialization/
