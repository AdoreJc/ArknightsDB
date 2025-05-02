# DelegateEntry

**Namespace:** ` `


## Fields

- `String type`

- `String assembly`

- `Object target`

- `String targetTypeAssembly`

- `String targetTypeName`

- `String methodName`

- `DelegateEntry delegateEntry`


## Methods

- `Delegate DeserializeDelegate(SerializationInfo, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class DelegateEntry
{
	private String type; // 0x10
	private String assembly; // 0x18
	private Object target; // 0x20
	private String targetTypeAssembly; // 0x28
	private String targetTypeName; // 0x30
	private String methodName; // 0x38
	public DelegateEntry delegateEntry; // 0x40


	// RVA: 0x6100540 VA: 0x7598718540
	public Void .ctor(Delegate del, String targetLabel) { }
	// RVA: 0x61002c8 VA: 0x75987182c8
	public Delegate DeserializeDelegate(SerializationInfo info, Int32 index) { }
}
```