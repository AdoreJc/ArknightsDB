# HeaderInfo

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class HeaderInfo
{
	internal readonly Boolean IsRequestRestricted; // 0x10
	internal readonly Boolean IsResponseRestricted; // 0x11
	internal readonly HeaderParser Parser; // 0x18
	internal readonly String HeaderName; // 0x20
	internal readonly Boolean AllowMultiValues; // 0x28


	// RVA: 0x6430c6c VA: 0x7598a48c6c
	internal Void .ctor(String name, Boolean requestRestricted, Boolean responseRestricted, Boolean multi, HeaderParser p) { }
}
```