# SyncLifeCycleContext

**Namespace:** ` `


## Fields

- `Boolean isBusy`

- `PlayerSyncStatusViewModel syncViewModel`


## Methods

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SyncLifeCycleContext : IHotfixable
{
	public Boolean isBusy; // 0x10
	public List`1 syncingList; // 0x18
	public List`1 serviceCodeList; // 0x20
	public PlayerSyncStatusViewModel syncViewModel; // 0x28
	private static DelegateBridge __Hotfix0_Clear; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x21fc0c0 VA: 0x75948140c0
	public Void Clear() { }
	// RVA: 0x21fc1a8 VA: 0x75948141a8
	public Void .ctor() { }
}
```