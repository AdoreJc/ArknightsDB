# RelicCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `RelicProperty relic`


## Methods

- `Void SetSelectedRelicItem(String)`

- `Void SetFilterMethod(FilterRule)`

- `Void SwitchDifficulty(Int32)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class RelicCompInfo : ActArchiveCompInfo
{
	public RelicProperty relic; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedRelicItem; // 0x8
	private static DelegateBridge __Hotfix0_SetFilterMethod; // 0x10
	private static DelegateBridge __Hotfix0_SwitchDifficulty; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30
	private static DelegateBridge __Hotfix0_IsValid; // 0x38
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x40


	// RVA: 0x307d284 VA: 0x7595695284
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x307d30c VA: 0x759569530c
	public Void SetSelectedRelicItem(String relicId) { }
	// RVA: 0x307d470 VA: 0x7595695470
	public Void SetFilterMethod(FilterRule rule) { }
	// RVA: 0x307d550 VA: 0x7595695550
	public Void SwitchDifficulty(Int32 toward) { }
	// RVA: 0x307d694 VA: 0x7595695694
	public override Void LoadData(String archiveId) { }
	// RVA: 0x307d7d0 VA: 0x75956957d0
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x307d880 VA: 0x7595695880
	public override Void NotifyUpdate() { }
	// RVA: 0x307d928 VA: 0x7595695928
	public override Boolean IsValid() { }
	// RVA: 0x307d9b4 VA: 0x75956959b4
	public override Boolean HasNewItem() { }
	// RVA: 0x307da6c VA: 0x7595695a6c
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```