# AssetWrapper

**Namespace:** ` `


## Fields

- `AssetGroupRecord m_globalGroupRecord`

- `Int32 instId`

- `String path`


## Properties

- `Boolean isRefered`


## Methods

- `Void AddGroupRef(Int32)`

- `Void RemoveGroupRef(Int32)`

- `Void ClearAllRefs()`

- `Boolean get_isRefered()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class AssetWrapper : IHotfixable
{
	private List`1 m_referGroups; // 0x10
	private AssetGroupRecord m_globalGroupRecord; // 0x18
	public Int32 instId; // 0x20
	public String path; // 0x28
	private static __XLua_Gen_Delegate137 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate11 __Hotfix0_AddGroupRef; // 0x8
	private static __XLua_Gen_Delegate11 __Hotfix0_RemoveGroupRef; // 0x10
	private static __XLua_Gen_Delegate1 __Hotfix0_ClearAllRefs; // 0x18
	private static __XLua_Gen_Delegate8 __Hotfix0_get_isRefered; // 0x20

	public Boolean isRefered { get; }

	// RVA: 0x6794728 VA: 0x7598dac728
	public Void .ctor(Int32 instId, String path, AssetGroupRecord record, Int32 initGroup) { }
	// RVA: 0x67945f8 VA: 0x7598dac5f8
	public Void AddGroupRef(Int32 group) { }
	// RVA: 0x67959ec VA: 0x7598dad9ec
	public Void RemoveGroupRef(Int32 group) { }
	// RVA: 0x6795c20 VA: 0x7598dadc20
	public Void ClearAllRefs() { }
	// RVA: 0x6795ddc VA: 0x7598dadddc
	public Boolean get_isRefered() { }
}
```