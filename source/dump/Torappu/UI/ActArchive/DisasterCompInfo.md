# DisasterCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `DisasterProperty disaster`


## Methods

- `Void SetSelectedDisasterId(String)`

- `Void SetShowSwitchAnim(Boolean)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DisasterCompInfo : ActArchiveCompInfo, IHotfixable
{
	public DisasterProperty disaster; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedDisasterId; // 0x8
	private static DelegateBridge __Hotfix0_SetShowSwitchAnim; // 0x10
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x18
	private static DelegateBridge __Hotfix0_IsValid; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x38


	// RVA: 0x304b610 VA: 0x7595663610
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x304b698 VA: 0x7595663698
	public Void SetSelectedDisasterId(String disasterTypeId) { }
	// RVA: 0x304b77c VA: 0x759566377c
	public Void SetShowSwitchAnim(Boolean show) { }
	// RVA: 0x304b830 VA: 0x7595663830
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x304b8e0 VA: 0x75956638e0
	public override Boolean IsValid() { }
	// RVA: 0x304b96c VA: 0x759566396c
	public override Void LoadData(String archiveId) { }
	// RVA: 0x304ba98 VA: 0x7595663a98
	public override Void NotifyUpdate() { }
	// RVA: 0x304bb40 VA: 0x7595663b40
	public override Boolean HasNewItem() { }
	// RVA: 0x304bbe8 VA: 0x7595663be8
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```