# BattleFinishHandBookStageViewModel

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `BattleInfoViewModel m_infoViewModel`

- `HandBookDropInfoViewModel m_droupInfoGroupModel`


## Properties

- `PlayerBattleRank rank`

- `String stageName`

- `BattleInfoViewModel infoModel`

- `HandBookDropInfoViewModel droupInfoGroupModel`


## Methods

- `PlayerBattleRank get_rank()`

- `String get_stageName()`

- `BattleInfoViewModel get_infoModel()`

- `HandBookDropInfoViewModel get_droupInfoGroupModel()`

- `Void LoadData()`

- `Void _LoadBattleInfoModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHandBookStageViewModel : IHotfixable
{
	private BattleInfoViewModel m_infoViewModel; // 0x10
	private HandBookDropInfoViewModel m_droupInfoGroupModel; // 0x18
	private static DelegateBridge __Hotfix0_get_rank; // 0x0
	private static DelegateBridge __Hotfix0_get_stageName; // 0x8
	private static DelegateBridge __Hotfix0_get_infoModel; // 0x10
	private static DelegateBridge __Hotfix0_get_droupInfoGroupModel; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0__LoadBattleInfoModel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public PlayerBattleRank rank { get; }
	public String stageName { get; }
	public BattleInfoViewModel infoModel { get; }
	public HandBookDropInfoViewModel droupInfoGroupModel { get; }

	// RVA: 0x2e89ce0 VA: 0x75954a1ce0
	public PlayerBattleRank get_rank() { }
	// RVA: 0x2e89d54 VA: 0x75954a1d54
	public String get_stageName() { }
	// RVA: 0x2e89dc8 VA: 0x75954a1dc8
	public BattleInfoViewModel get_infoModel() { }
	// RVA: 0x2e89e30 VA: 0x75954a1e30
	public HandBookDropInfoViewModel get_droupInfoGroupModel() { }
	// RVA: 0x2e89e98 VA: 0x75954a1e98
	public Void LoadData() { }
	// RVA: 0x2e89f00 VA: 0x75954a1f00
	private Void _LoadBattleInfoModel() { }
	// RVA: 0x2e8a610 VA: 0x75954a2610
	public Void .ctor() { }
}
```