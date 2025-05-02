# FragmentCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `FragmentProperty fragment`


## Methods

- `Void SetSelectedItemId(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class FragmentCompInfo : ActArchiveCompInfo, IHotfixable
{
	public FragmentProperty fragment; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedItemId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x3056d94 VA: 0x759566ed94
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3056e1c VA: 0x759566ee1c
	public Void SetSelectedItemId(String fragmentId) { }
	// RVA: 0x3056f00 VA: 0x759566ef00
	public override Void LoadData(String archiveId) { }
	// RVA: 0x305701c VA: 0x759566f01c
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x30570cc VA: 0x759566f0cc
	public override Void NotifyUpdate() { }
	// RVA: 0x3057174 VA: 0x759566f174
	public override Boolean IsValid() { }
	// RVA: 0x3057200 VA: 0x759566f200
	public override Boolean HasNewItem() { }
	// RVA: 0x30572b8 VA: 0x759566f2b8
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```