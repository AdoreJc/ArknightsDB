# ArgInfo

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Int32 _inoutArgCount`

- `MethodBase _method`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class ArgInfo
{
	private Int32[] _paramMap; // 0x10
	private Int32 _inoutArgCount; // 0x18
	private MethodBase _method; // 0x20


	// RVA: 0x5fa0540 VA: 0x75985b8540
	public Void .ctor(MethodBase method, ArgInfoType type) { }
	// RVA: 0x5fa0714 VA: 0x75985b8714
	public Object[] GetInOutArgs(Object[] args) { }
}
```