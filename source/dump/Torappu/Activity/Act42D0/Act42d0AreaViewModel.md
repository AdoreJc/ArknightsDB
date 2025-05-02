# Act42d0AreaViewModel

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0AreaInfoData areaInfo`

- `Boolean isUnlock`

- `String unlockDesc`

- `Boolean canUseBuff`

- `String activityId`

- `Int32 m_stageSelectedIndex`


## Properties

- `Int32 stageSelectedIndex`

- `Boolean hasStageSelected`


## Methods

- `Int32 get_stageSelectedIndex()`

- `Boolean get_hasStageSelected()`

- `Void LoadData(String, Act42D0AreaInfoData)`

- `Boolean IsNew()`

- `Void RefreshPlayerData(AreaInfo)`

- `Void SelectStage(String)`

- `Void UnSelect()`

- `Void SelectStage(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42d0AreaViewModel : IHotfixable
{
	public Act42D0AreaInfoData areaInfo; // 0x10
	public Boolean isUnlock; // 0x18
	public String unlockDesc; // 0x20
	public Boolean canUseBuff; // 0x28
	public String activityId; // 0x30
	public const Int32 STAGE_INDEX_NO_SELECTTION; // 0x0
	public List`1 stageItemModelList; // 0x38
	private Dictionary`2 m_stageRatingInfoData; // 0x40
	private Int32 m_stageSelectedIndex; // 0x48
	private static DelegateBridge __Hotfix0_get_stageSelectedIndex; // 0x0
	private static DelegateBridge __Hotfix0_get_hasStageSelected; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_IsNew; // 0x18
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x20
	private static DelegateBridge __Hotfix0_SelectStage; // 0x28
	private static DelegateBridge __Hotfix0_UnSelect; // 0x30
	private static DelegateBridge __Hotfix1_SelectStage; // 0x38
	private static DelegateBridge __Hotfix0_IfHasStageSelected; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 stageSelectedIndex { get; }
	public Boolean hasStageSelected { get; }

	// RVA: 0x3219e14 VA: 0x7595831e14
	public Int32 get_stageSelectedIndex() { }
	// RVA: 0x3219e7c VA: 0x7595831e7c
	public Boolean get_hasStageSelected() { }
	// RVA: 0x3218c48 VA: 0x7595830c48
	public Void LoadData(String actId, Act42D0AreaInfoData areaInfoData) { }
	// RVA: 0x32176a0 VA: 0x759582f6a0
	public Boolean IsNew() { }
	// RVA: 0x32198ec VA: 0x75958318ec
	public Void RefreshPlayerData(AreaInfo playerInfo) { }
	// RVA: 0x3219678 VA: 0x7595831678
	public Void SelectStage(String stageId) { }
	// RVA: 0x3219cc8 VA: 0x7595831cc8
	public Void UnSelect() { }
	// RVA: 0x3219f5c VA: 0x7595831f5c
	public Void SelectStage(Int32 stageIndex) { }
	// RVA: 0x3219fd8 VA: 0x7595831fd8
	public static Boolean IfHasStageSelected(Int32 index) { }
	// RVA: 0x3218b34 VA: 0x7595830b34
	public Void .ctor() { }
}
```