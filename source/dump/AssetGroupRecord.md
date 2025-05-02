# AssetGroupRecord

**Namespace:** ` `


## Methods

- `Void AddRef(Int32, Int32)`

- `Void RemoveRef(Int32, Int32)`

- `Void Dispose()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class AssetGroupRecord : IHotfixable, IDisposable
{
	private Dictionary`2 m_groupToAssets; // 0x10
	private static __XLua_Gen_Delegate138 __Hotfix0_AddRef; // 0x0
	private static __XLua_Gen_Delegate138 __Hotfix0_RemoveRef; // 0x8
	private static __XLua_Gen_Delegate139 __Hotfix0_GetRefedAssets; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_Dispose; // 0x18
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x20


	// RVA: 0x6795874 VA: 0x7598dad874
	public Void AddRef(Int32 group, Int32 asset) { }
	// RVA: 0x6795aa8 VA: 0x7598dadaa8
	public Void RemoveRef(Int32 group, Int32 asset) { }
	// RVA: 0x6794f3c VA: 0x7598dacf3c
	public IEnumerator`1 GetRefedAssets(Int32 group) { }
	// RVA: 0x6795774 VA: 0x7598dad774
	public Void Dispose() { }
	// RVA: 0x6793dc0 VA: 0x7598dabdc0
	public Void .ctor() { }
}
```