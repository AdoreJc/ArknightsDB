# TotemCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `TotemProperty totem`


## Methods

- `Void SetSelectedTotemId(String)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TotemCompInfo : ActArchiveCompInfo
{
	public TotemProperty totem; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedTotemId; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x30


	// RVA: 0x308da88 VA: 0x75956a5a88
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x308db10 VA: 0x75956a5b10
	public Void SetSelectedTotemId(String totemId) { }
	// RVA: 0x308dbf4 VA: 0x75956a5bf4
	public override Void LoadData(String archiveId) { }
	// RVA: 0x308dd30 VA: 0x75956a5d30
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x308dde0 VA: 0x75956a5de0
	public override Void NotifyUpdate() { }
	// RVA: 0x308de88 VA: 0x75956a5e88
	public override Boolean IsValid() { }
	// RVA: 0x308df14 VA: 0x75956a5f14
	public override Boolean HasNewItem() { }
	// RVA: 0x308dfcc VA: 0x75956a5fcc
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```