# 第九章 类模板参数推导
C++17之前，你必须为所有类模板显式指定模板参数类型。比如，你不能忽略这里的double：
```cpp
std::complex<double> c{5.1,3.3};
```