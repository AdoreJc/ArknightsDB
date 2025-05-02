# TransparentProxy

**Namespace:** `System.Runtime.Remoting.Proxies`


## Fields

- `RealProxy _rp`

- `RuntimeRemoteClassHandle _class`

- `Boolean _custom_type_info`


## Properties

- `Boolean IsContextBoundObject`

- `Context TargetContext`


## Methods

- `Boolean get_IsContextBoundObject()`

- `Context get_TargetContext()`

- `Boolean InCurrentContext()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Proxies
internal class TransparentProxy
{
	public RealProxy _rp; // 0x10
	private RuntimeRemoteClassHandle _class; // 0x18
	private Boolean _custom_type_info; // 0x20

	private Boolean IsContextBoundObject { get; }
	private Context TargetContext { get; }

	// RVA: 0x5f8e3e8 VA: 0x75985a63e8
	internal RuntimeType GetProxyType() { }
	// RVA: 0x5f8e4b8 VA: 0x75985a64b8
	private Boolean get_IsContextBoundObject() { }
	// RVA: 0x5f8e4d4 VA: 0x75985a64d4
	private Context get_TargetContext() { }
	// RVA: 0x5f8e4f0 VA: 0x75985a64f0
	private Boolean InCurrentContext() { }
	// RVA: 0x5f8e530 VA: 0x75985a6530
	internal Object LoadRemoteFieldNew(IntPtr classPtr, IntPtr fieldPtr) { }
	// RVA: 0x5f8f280 VA: 0x75985a7280
	internal Void StoreRemoteField(IntPtr classPtr, IntPtr fieldPtr, Object arg) { }
	// RVA: 0x5f8f57c VA: 0x75985a757c
	public Void .ctor() { }
}
```