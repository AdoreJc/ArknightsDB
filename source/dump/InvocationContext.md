# InvocationContext

**Namespace:** ` `


## Fields

- `SendOrPostCallback m_Delegate`

- `Object m_State`


## Methods

- `Void Invoke()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class InvocationContext
{
	private SendOrPostCallback m_Delegate; // 0x10
	private Object m_State; // 0x18


	// RVA: 0x6122264 VA: 0x759873a264
	public Void .ctor(SendOrPostCallback d, Object state) { }
	// RVA: 0x61222ac VA: 0x759873a2ac
	public Void Invoke() { }
}
```