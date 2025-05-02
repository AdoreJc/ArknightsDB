# CrisisV2AchievementViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Int32 seasonCount`

- `Int32 selectIndex`

- `Boolean isFastMode`


## Properties

- `Boolean showSwitchBtn`

- `CrisisV2AchievementSeasonViewModel currentSeasonModel`


## Methods

- `Boolean get_showSwitchBtn()`

- `CrisisV2AchievementSeasonViewModel get_currentSeasonModel()`

- `Void LoadData()`

- `Void SetSelectIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementViewModel : IHotfixable
{
	public Int32 seasonCount; // 0x10
	public Int32 selectIndex; // 0x14
	public List`1 seasonList; // 0x18
	public Boolean isFastMode; // 0x20
	private static DelegateBridge __Hotfix0_get_showSwitchBtn; // 0x0
	private static DelegateBridge __Hotfix0_get_currentSeasonModel; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean showSwitchBtn { get; }
	public CrisisV2AchievementSeasonViewModel currentSeasonModel { get; }

	// RVA: 0x2be4cdc VA: 0x75951fccdc
	public Boolean get_showSwitchBtn() { }
	// RVA: 0x2be4d4c VA: 0x75951fcd4c
	public CrisisV2AchievementSeasonViewModel get_currentSeasonModel() { }
	// RVA: 0x2be4dd4 VA: 0x75951fcdd4
	public Void LoadData() { }
	// RVA: 0x2be57a8 VA: 0x75951fd7a8
	public Void SetSelectIndex(Int32 index) { }
	// RVA: 0x2be5848 VA: 0x75951fd848
	public Void .ctor() { }
}
```