# Act1LockBattleFinishViewModel

**Namespace:** `Torappu.Activity.Act1Lock.BattleFinish`


## Fields

- `Boolean isValid`

- `String activityId`

- `String stageId`

- `Sprite spriteBlurBkg`

- `BattleInfoViewModel battleInfoModel`

- `ControlModel expBarControlModel`

- `Int32 curLevel`

- `Int32 curExp`

- `Boolean needShowLvlUp`

- `DropInfoGroupViewModel dropInfoModel`

- `Boolean hasDrop`

- `FinalStagePointModel finalStagePointModel`

- `InterlockStageDefendModel interlockStageDefendModel`

- `CommonFinishBattleResponse m_cachedResponse`

- `ActivityInterlockData m_cachedActData`

- `PlayerInterlockActivity m_cachedPlayerActData`


## Methods

- `Void LoadData(CommonFinishBattleResponse)`

- `Void _LoadBattleInfo()`

- `Void _LoadExpInfo()`

- `Void _LoadDropInfo()`

- `Void _LoadFinalStagePointModel()`

- `Void _LoadInterlockStageDefendModel()`

- `Int32 _CalcAddExp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.BattleFinish
public class Act1LockBattleFinishViewModel : IHotfixable
{
	public Boolean isValid; // 0x10
	public String activityId; // 0x18
	public String stageId; // 0x20
	public Sprite spriteBlurBkg; // 0x28
	public BattleInfoViewModel battleInfoModel; // 0x30
	public ControlModel expBarControlModel; // 0x38
	public Int32 curLevel; // 0x40
	public Int32 curExp; // 0x44
	public Boolean needShowLvlUp; // 0x48
	public DropInfoGroupViewModel dropInfoModel; // 0x50
	public Boolean hasDrop; // 0x58
	public FinalStagePointModel finalStagePointModel; // 0x60
	public InterlockStageDefendModel interlockStageDefendModel; // 0x68
	private CommonFinishBattleResponse m_cachedResponse; // 0x70
	private ActivityInterlockData m_cachedActData; // 0x78
	private PlayerInterlockActivity m_cachedPlayerActData; // 0x80
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__LoadBattleInfo; // 0x8
	private static DelegateBridge __Hotfix0__LoadExpInfo; // 0x10
	private static DelegateBridge __Hotfix0__LoadDropInfo; // 0x18
	private static DelegateBridge __Hotfix0__LoadFinalStagePointModel; // 0x20
	private static DelegateBridge __Hotfix0__LoadInterlockStageDefendModel; // 0x28
	private static DelegateBridge __Hotfix0__CalcAddExp; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x33e011c VA: 0x75959f811c
	public Void LoadData(CommonFinishBattleResponse response) { }
	// RVA: 0x33e0408 VA: 0x75959f8408
	private Void _LoadBattleInfo() { }
	// RVA: 0x33e063c VA: 0x75959f863c
	private Void _LoadExpInfo() { }
	// RVA: 0x33e07d8 VA: 0x75959f87d8
	private Void _LoadDropInfo() { }
	// RVA: 0x33e0a14 VA: 0x75959f8a14
	private Void _LoadFinalStagePointModel() { }
	// RVA: 0x33e0e18 VA: 0x75959f8e18
	private Void _LoadInterlockStageDefendModel() { }
	// RVA: 0x33e1958 VA: 0x75959f9958
	private Int32 _CalcAddExp() { }
	// RVA: 0x33e1d28 VA: 0x75959f9d28
	public Void .ctor() { }
}
```