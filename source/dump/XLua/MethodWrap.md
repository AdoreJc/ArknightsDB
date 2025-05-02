# MethodWrap

**Namespace:** `XLua`


## Fields

- `String methodName`

- `Boolean forceCheck`


## Methods

- `Int32 Call(IntPtr)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class MethodWrap
{
	private String methodName; // 0x10
	private List`1 overloads; // 0x18
	private Boolean forceCheck; // 0x20


	// RVA: 0x3fe9240 VA: 0x7596601240
	public Void .ctor(String methodName, List`1 overloads, Boolean forceCheck) { }
	// RVA: 0x3fe9314 VA: 0x7596601314
	public Int32 Call(IntPtr L) { }
}
```