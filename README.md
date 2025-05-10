|Type|Prefix|Example|Description|
|:---:|:---:|:---:|:---:|
|parameter|_|int _iValue|Personal preference. Necessary in order to differentiate constructor arguments such as x(_x), y(_y), z(_z)|
|bool|b|bool bExit||
|class|cl|CFoo clFoo|Personal preference. Necessary in order to clarify variable is object|
|char|c|char cCharacter|Personal preference over ch|
|double|d|double dValue||
|enum / enum class|e|EType eType||
|float|f|float fValue||
|global|g_|CFoo g_app||
|int|i|int iCount|n seems more widely used. However, it becomes difficult to differentiate union. ex) unsigned int un vs unsigned u vs union ?|
|long|l|long lValue||
|long long|ll|long long llValue||
|member variable|m_|int m_iCount||
|pointer|p|void* pBuffer||
|reference|ref|CFoo& refFoo|[Referenced C# ref](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/ref)|
|short|s|short sValue||
|static|s_|int s_iValue||
|struct|st|[SYSTEMTIME](https://learn.microsoft.com/en-us/windows/win32/api/minwinbase/ns-minwinbase-systemtime) stSystemTime||
|||SMat4x4f stMat4x4f||
|union|un|[LARGE_INTEGER](https://learn.microsoft.com/en-us/windows/win32/api/winnt/ns-winnt-large_integer-r1) uLargeInteger||
|unsigned|u|unsigned char ucValue||
|||unsigned short usValue||
|||unsigned int uiValue||
|||unsigned long ulValue||
|||unsigned long long ullValue||

## References
- [Hungarian Notation, Wikipedia](https://en.wikipedia.org/wiki/Hungarian_notation)
- [Hungarian Notation for C/C++](https://brising.com/hungarian-notation-for-c-c/)
- [Coding Style Conventions](https://learn.microsoft.com/en-us/windows/win32/stg/coding-style-conventions)
