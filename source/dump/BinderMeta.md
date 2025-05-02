# BinderMeta

**Namespace:** ` `


## Fields

- `IBindLocalTrackStore binder`

- `TrackPointBinderKey key`

- `IDObserver observer`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BinderMeta : IHotfixable
{
	public IBindLocalTrackStore binder; // 0x10
	public TrackPointBinderKey key; // 0x18
	public IDObserver observer; // 0x28
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f3de08 VA: 0x7595555e08
	public static Void Reset(BinderMeta inst) { }
	// RVA: 0x2f3de90 VA: 0x7595555e90
	public Void .ctor() { }
}
```