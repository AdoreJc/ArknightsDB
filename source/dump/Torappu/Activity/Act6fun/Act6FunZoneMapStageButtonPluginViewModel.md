# Act6FunZoneMapStageButtonPluginViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `String stageCode`

- `Int32 curAchievementCount`

- `Int32 maxAchievementCount`

- `Boolean showItem`

- `Boolean showAchievementInfo`

- `Boolean isUnlocked`

- `Boolean isComplete`

- `Act6FunStageAdditionData m_additionData`

- `PlayerStageState m_stageState`


## Methods

- `Void LoadData(StageViewModel, Act6FunData)`

- `Void RefreshData(StageViewModel, PlayerActFun6Stage)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapStageButtonPluginViewModel : IHotfixable
{
	public String stageCode; // 0x10
	public Int32 curAchievementCount; // 0x18
	public Int32 maxAchievementCount; // 0x1c
	public Boolean showItem; // 0x20
	public Boolean showAchievementInfo; // 0x21
	public Boolean isUnlocked; // 0x22
	public Boolean isComplete; // 0x23
	private Act6FunStageAdditionData m_additionData; // 0x28
	private PlayerStageState m_stageState; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31b2f2c VA: 0x75957caf2c
	public Void LoadData(StageViewModel stageViewModel, Act6FunData act6FunData) { }
	// RVA: 0x31b3094 VA: 0x75957cb094
	public Void RefreshData(StageViewModel stageViewModel, PlayerActFun6Stage playerActFun6Stage) { }
	// RVA: 0x31b319c VA: 0x75957cb19c
	public Void .ctor() { }
}
```