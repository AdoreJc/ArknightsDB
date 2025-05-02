# ClimbTowerLevelModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String levelId`

- `String levelPath`

- `String levelName`

- `String levelCode`

- `String levelDesc`

- `Int32 layerNum`

- `ClimbTowerLevelType levelType`

- `String levelPreviewMapId`


## Methods

- `Void LoadData(String, Boolean)`

- `Void _LoadRewardData(ClimbTowerSingleLevelData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLevelModel : IHotfixable
{
	public String levelId; // 0x10
	public String levelPath; // 0x18
	public String levelName; // 0x20
	public String levelCode; // 0x28
	public String levelDesc; // 0x30
	public Int32 layerNum; // 0x38
	public ClimbTowerLevelType levelType; // 0x3c
	public String levelPreviewMapId; // 0x40
	public List`1 displayRewards; // 0x48
	public List`1 displayDetailRewards; // 0x50
	public List`1 offerDisplayDetailRewards; // 0x58
	public Dictionary`2 rewardInfos; // 0x60
	public Dictionary`2 offerRewardInfos; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadRewardData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2cdafac VA: 0x75952f2fac
	public Void LoadData(String level, Boolean isHardMode) { }
	// RVA: 0x2cdb8e4 VA: 0x75952f38e4
	private Void _LoadRewardData(ClimbTowerSingleLevelData levelData) { }
	// RVA: 0x2cdaf3c VA: 0x75952f2f3c
	public Void .ctor() { }
}
```