# Act6FunZoneMapAchievePluginViewModel

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `Int32 <curAchievementCount>k__BackingField`

- `Int32 <maxAchievementCount>k__BackingField`


## Properties

- `Int32 curAchievementCount`

- `Int32 maxAchievementCount`


## Methods

- `Int32 get_curAchievementCount()`

- `Void set_curAchievementCount(Int32)`

- `Int32 get_maxAchievementCount()`

- `Void set_maxAchievementCount(Int32)`

- `Void LoadData(Act6FunData)`

- `Void RefreshByPlayerData(PlayerActFun6)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneMapAchievePluginViewModel : IHotfixable
{
	private Int32 <curAchievementCount>k__BackingField; // 0x10
	private Int32 <maxAchievementCount>k__BackingField; // 0x14
	private List`1 m_rewardsItemList; // 0x18
	private List`1 m_progressItemList; // 0x20
	private static DelegateBridge __Hotfix0_get_curAchievementCount; // 0x0
	private static DelegateBridge __Hotfix0_set_curAchievementCount; // 0x8
	private static DelegateBridge __Hotfix0_get_maxAchievementCount; // 0x10
	private static DelegateBridge __Hotfix0_set_maxAchievementCount; // 0x18
	private static DelegateBridge __Hotfix0_get_rewardsItemList; // 0x20
	private static DelegateBridge __Hotfix0_get_progressItemList; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshByPlayerData; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 curAchievementCount { get; set; }
	public Int32 maxAchievementCount { get; set; }
	public List`1 rewardsItemList { get; }
	public List`1 progressItemList { get; }

	// RVA: 0x31b219c VA: 0x75957ca19c
	public Int32 get_curAchievementCount() { }
	// RVA: 0x31b2204 VA: 0x75957ca204
	private Void set_curAchievementCount(Int32 value) { }
	// RVA: 0x31b2280 VA: 0x75957ca280
	public Int32 get_maxAchievementCount() { }
	// RVA: 0x31b22e8 VA: 0x75957ca2e8
	private Void set_maxAchievementCount(Int32 value) { }
	// RVA: 0x31b2364 VA: 0x75957ca364
	public List`1 get_rewardsItemList() { }
	// RVA: 0x31b23cc VA: 0x75957ca3cc
	public List`1 get_progressItemList() { }
	// RVA: 0x31b2434 VA: 0x75957ca434
	public Void LoadData(Act6FunData actData) { }
	// RVA: 0x31b2a10 VA: 0x75957caa10
	public Void RefreshByPlayerData(PlayerActFun6 playerActFun6Data) { }
	// RVA: 0x31b2d28 VA: 0x75957cad28
	public Void .ctor() { }
}
```