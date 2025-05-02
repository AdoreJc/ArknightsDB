# Act6FunZoneMapStagePreviewPluginViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Int64 <passTime>k__BackingField`

- `String <npcDialog>k__BackingField`

- `String <charPicId>k__BackingField`


## Properties

- `Int64 passTime`

- `String npcDialog`

- `String charPicId`


## Methods

- `Int64 get_passTime()`

- `Void set_passTime(Int64)`

- `String get_npcDialog()`

- `Void set_npcDialog(String)`

- `String get_charPicId()`

- `Void set_charPicId(String)`

- `Void LoadData(String, Act6FunData)`

- `Void RefreshData(PlayerActFun6Stage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapStagePreviewPluginViewModel : IHotfixable
{
	private Int64 <passTime>k__BackingField; // 0x10
	private String <npcDialog>k__BackingField; // 0x18
	private String <charPicId>k__BackingField; // 0x20
	private List`1 m_achieveItemModelList; // 0x28
	private static DelegateBridge __Hotfix0_get_achieveItemModelList; // 0x0
	private static DelegateBridge __Hotfix0_get_passTime; // 0x8
	private static DelegateBridge __Hotfix0_set_passTime; // 0x10
	private static DelegateBridge __Hotfix0_get_npcDialog; // 0x18
	private static DelegateBridge __Hotfix0_set_npcDialog; // 0x20
	private static DelegateBridge __Hotfix0_get_charPicId; // 0x28
	private static DelegateBridge __Hotfix0_set_charPicId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_RefreshData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public List`1 achieveItemModelList { get; }
	public Int64 passTime { get; set; }
	public String npcDialog { get; set; }
	public String charPicId { get; set; }

	// RVA: 0x31b3814 VA: 0x75957cb814
	public List`1 get_achieveItemModelList() { }
	// RVA: 0x31b387c VA: 0x75957cb87c
	public Int64 get_passTime() { }
	// RVA: 0x31b38e4 VA: 0x75957cb8e4
	private Void set_passTime(Int64 value) { }
	// RVA: 0x31b3960 VA: 0x75957cb960
	public String get_npcDialog() { }
	// RVA: 0x31b39c8 VA: 0x75957cb9c8
	private Void set_npcDialog(String value) { }
	// RVA: 0x31b3a4c VA: 0x75957cba4c
	public String get_charPicId() { }
	// RVA: 0x31b3ab4 VA: 0x75957cbab4
	private Void set_charPicId(String value) { }
	// RVA: 0x31b3b38 VA: 0x75957cbb38
	public Void LoadData(String stageId, Act6FunData act6FunData) { }
	// RVA: 0x31b3df8 VA: 0x75957cbdf8
	public Void RefreshData(PlayerActFun6Stage playerActFun6Stage) { }
	// RVA: 0x31b3f9c VA: 0x75957cbf9c
	public Void .ctor() { }
}
```