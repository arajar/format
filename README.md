format
======

A simple header-only C++11 std::string formatter

Usage:
------

```c++

std::string test = util::Format("This is a nice string with numbers {0} and strings {1} nicely formatted", 123, "hello");
std::string test = util::Format("{0, 20}", "Formatting is nice!");
```
