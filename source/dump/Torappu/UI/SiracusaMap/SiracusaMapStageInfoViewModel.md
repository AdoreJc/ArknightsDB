# SiracusaMapStageInfoViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `StageViewModel <normalStage>k__BackingField`

- `StageViewModel hardStage`

- `Int32 sortId`

- `Int32 <rankNum>k__BackingField`

- `String <pointId>k__BackingField`


## Properties

- `StageViewModel normalStage`

- `Int32 rankNum`

- `String stageId`

- `String pointId`

- `StageViewModel normalStageModel`


## Methods

- `StageViewModel get_normalStage()`

- `Void set_normalStage(StageViewModel)`

- `Int32 get_rankNum()`

- `Void set_rankNum(Int32)`

- `String get_stageId()`

- `String get_pointId()`

- `Void set_pointId(String)`

- `StageViewModel get_normalStageModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageInfoViewModel : ISiracusaMapStageInfoModel, IHotfixable
{
	private StageViewModel <normalStage>k__BackingField; // 0x10
	public StageViewModel hardStage; // 0x18
	public Int32 sortId; // 0x20
	private Int32 <rankNum>k__BackingField; // 0x24
	private String <pointId>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_normalStage; // 0x0
	private static DelegateBridge __Hotfix0_set_normalStage; // 0x8
	private static DelegateBridge __Hotfix0_get_rankNum; // 0x10
	private static DelegateBridge __Hotfix0_set_rankNum; // 0x18
	private static DelegateBridge __Hotfix0_get_stageId; // 0x20
	private static DelegateBridge __Hotfix0_get_pointId; // 0x28
	private static DelegateBridge __Hotfix0_set_pointId; // 0x30
	private static DelegateBridge __Hotfix0_get_normalStageModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public StageViewModel normalStage { get; set; }
	public Int32 rankNum { get; set; }
	public String stageId { get; }
	public String pointId { get; set; }
	public StageViewModel normalStageModel { get; }

	// RVA: 0x2415d04 VA: 0x7594a2dd04
	public StageViewModel get_normalStage() { }
	// RVA: 0x2415d6c VA: 0x7594a2dd6c
	public Void set_normalStage(StageViewModel value) { }
	// RVA: 0x2415df0 VA: 0x7594a2ddf0
	public Int32 get_rankNum() { }
	// RVA: 0x2415e58 VA: 0x7594a2de58
	public Void set_rankNum(Int32 value) { }
	// RVA: 0x2415ed4 VA: 0x7594a2ded4
	public String get_stageId() { }
	// RVA: 0x2415f7c VA: 0x7594a2df7c
	public String get_pointId() { }
	// RVA: 0x2415fe4 VA: 0x7594a2dfe4
	public Void set_pointId(String value) { }
	// RVA: 0x2416068 VA: 0x7594a2e068
	public StageViewModel get_normalStageModel() { }
	// RVA: 0x24160d0 VA: 0x7594a2e0d0
	public Void .ctor() { }
}
```