# BaseSerializationDelegate

**Namespace:** `FullInspector.Modules`


## Fields

- `Object MethodContainer`

- `String MethodName`


## Properties

- `Boolean CanInvoke`


## Methods

- `Boolean get_CanInvoke()`

- `Object DoInvoke(Object[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Modules
public class BaseSerializationDelegate
{
	public Object MethodContainer; // 0x10
	public String MethodName; // 0x18

	public Boolean CanInvoke { get; }

	// RVA: 0x34d6514 VA: 0x7595aee514
	public Void .ctor() { }
	// RVA: 0x34d6568 VA: 0x7595aee568
	public Void .ctor(Object methodContainer, String methodName) { }
	// RVA: 0x34d65ac VA: 0x7595aee5ac
	public Boolean get_CanInvoke() { }
	// RVA: 0x34d6100 VA: 0x7595aee100
	protected Object DoInvoke(Object[] parameters) { }
}
```