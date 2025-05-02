# ActMultiV3StageListDetailStateViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Int32 normalStageCount`

- `Int32 selectedStageIndex`

- `ActMultiV3StageDetailViewModel stageViewModel`

- `String actId`


## Properties

- `String selectedStageId`


## Methods

- `String get_selectedStageId()`

- `Void LoadData(String, String)`

- `Void _ReloadStageViewModel()`

- `Void SetSelectedStage(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StageListDetailStateViewModel : IHotfixable
{
	public List`1 stageList; // 0x10
	public Int32 normalStageCount; // 0x18
	public Int32 selectedStageIndex; // 0x1c
	public ActMultiV3StageDetailViewModel stageViewModel; // 0x20
	public String actId; // 0x28
	private static DelegateBridge __Hotfix0_get_selectedStageId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0__ReloadStageViewModel; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectedStage; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String selectedStageId { get; }

	// RVA: 0x3148aa0 VA: 0x7595760aa0
	public String get_selectedStageId() { }
	// RVA: 0x31492c4 VA: 0x75957612c4
	public Void LoadData(String actId, String stageId) { }
	// RVA: 0x3149410 VA: 0x7595761410
	private Void _ReloadStageViewModel() { }
	// RVA: 0x3148f00 VA: 0x7595760f00
	public Void SetSelectedStage(Boolean isRight) { }
	// RVA: 0x31494d4 VA: 0x75957614d4
	public Void .ctor() { }
}
```