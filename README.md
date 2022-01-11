# Getting an Array Element Index

Beginner level task for practicing loops, arrays and extension methods.

In the task you have to implement six "GetIndexOfChar" methods that should return the zero-based index (position) of the first occurrence of the specified character ("value" parameter) in the string that is passed as a "str" parameter.


## Task Description

The implementation details are described with TODO comments in code files. There are fix "GetLastIndexOf" method that you can use as examples. Analyze these methods and run unit tests for them before starting implementing methods you have to implement.

It's allowed to use [Array.Length](https://docs.microsoft.com/en-us/dotnet/api/system.array.length) and [Array.IList.Item](https://docs.microsoft.com/en-us/dotnet/api/system.array.system-collections-ilist-item) properties only for solving the task. You are not allowed to use other static or instance methods of the [Array class](https://docs.microsoft.com/en-us/dotnet/api/system.array) or any extension method from [System.Linq namespace](https://docs.microsoft.com/en-us/dotnet/api/system.linq).

1. Analyze the implementation of the "GetLastIndexOf(uint[], uint)" method in the [ForMethods.cs](GettingArrayElementIndex/ForMethods.cs#L19) file. Implement "GetIndexOfChar(uint[], uint)" static method. See TODO #1.
1. Analyze the implementation of the "GetLastIndexOf(uint[], uint, int, int)" method in the [ForMethods.cs](GettingArrayElementIndex/ForMethods.cs#L37) file. Implement "GetIndexOfChar(uint[], uint, int, int)" static method. See TODO #2.
1. Analyze the implementation of the "GetLastIndexOf(ushort[], ushort)" method in the [WhileMethods.cs](GettingArrayElementIndex/WhileMethods.cs#L19) file. Implement "GetIndexOfChar(ushort[], ushort)" static method. See TODO #3.
1. Analyze the implementation of the "GetLastIndexOf(ushort[], ushort, int, int)" method in the [WhileMethods.cs](GettingArrayElementIndex/WhileMethods.cs#L40) file. Implement "GetIndexOfChar(ushort[], ushort, int, int)" static method. See TODO #4.
1. Analyze the implementation of the "GetLastIndexOf(ulong[], ulong)" method in the [DoWhileMethods.cs](GettingArrayElementIndex/DoWhileMethods.cs#L19) file. Implement "GetIndexOfChar(ulong[], ulong)" static method. See TODO #5.
1. Analyze the implementation of the "GetLastIndexof(ulong[], ulong, int, int)" method in the [DoWhileMethods.cs](GettingArrayElementIndex/DoWhileMethods.cs#L44) file. Implement "GetIndexOfChar(ulong[], ulong, int, int) static method. See TODO #6.


## Fix Compiler Issues

Additional style and code checks are enabled for the projects in this solution to help you maintaining consistency of the project source code and avoiding silly mistakes. [Review the Error List](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-the-error-list) in Visual Studio to see all compiler warnings and errors.

If a compiler error or warning message is not clear, [review errors details](https://docs.microsoft.com/en-us/visualstudio/ide/find-and-fix-code-errors#review-errors-in-detail) or google the error or warning code to get more information about the issue.


## Task Checklist

1. Rebuild the solution.
1. Fix all compiler warnings and errors.
1. Run all unit tests, make sure all unit tests completed successfully.
1. Review all changes, make sure the only code files (.cs) in Bools project have changes. No changes in project files (.csproj) or in Bools.Tests project.
1. Stage your changes, and create a commit.
1. Push your changes to remote repository.


## See also

* C# Reference
  * [for statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/for)
  * [while statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/while)
  * [do..while statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/do)
  * [foreach..in statement](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/foreach-in)
  * [Increment operator ++](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/arithmetic-operators#increment-operator-)
  * [Decrement operator --](https://docs.microsoft.com/en-us/dotnet/csharp/language-reference/operators/arithmetic-operators#decrement-operator---)
  * [Creating and Throwing Exceptions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/exceptions/creating-and-throwing-exceptions)
* C# Programming Guide
  * [Extension Methods](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/extension-methods)
  * [How to implement and call a custom extension method](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/how-to-implement-and-call-a-custom-extension-method)
* .NET API
  * [Array.Length](https://docs.microsoft.com/en-us/dotnet/api/system.array.length)
  * [Array.IList.Item](https://docs.microsoft.com/en-us/dotnet/api/system.array.system-collections-ilist-item)
