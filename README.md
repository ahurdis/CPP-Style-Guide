# CPP-Style-Guide
C++ Style Guide

**Variable Initialization**  
  Use = whenever you can.  
  `
    int i {0};
  `  
  
  Use initializer-list syntax {} only for element initializers (of containers and aggregates).  
  `
    std::vector<int> v {1, 2, 3, 4};
  `  
  
  Use function-call syntax () to call a constructor, viewed as an object-factory.  
  `
    Widget w(name, price, quantity);
  `  
  
  -  Note, because of Guaranteed Copy Elision, we can write:  
  `
    auto w = Widget(name, price, quantity);  
  `
  
  [Reference](https://quuxplusone.github.io/blog/2019/02/18/knightmare-of-initialization/)

**Some Other Guideline** 
