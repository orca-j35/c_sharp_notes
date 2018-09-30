# C# 笔记

.NET 框架由以下三部分组成：

- CLR (Common Language Runtime)：公共语言运行库，CLR 在运行时管理程序的执行
- 编程工具：涵盖编码和调试所需的一切，包括 IDE、.NET 兼容的编译器、调试器以及网站开发的服务器端技术
- BCL(Base Class Library)：基类库，是 .NET 框架使用的一个大的类库，也可在自己的程序中使用

术语：

CIL(Common Intermediate Language)：公共中间语言

托管代码：为 .NET 框架编写的代码称为托管代码(managed code)，需要 CLR

非托管代码：不再 CLR 控制之下运行的代码，称为非托管代码(unmanaged code)，比如Win32 C/C++ DLL