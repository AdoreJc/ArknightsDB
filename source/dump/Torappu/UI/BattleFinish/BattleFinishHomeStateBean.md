# BattleFinishHomeStateBean

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `CommonBattleFinishModel m_battleFinishModel`


## Properties

- `CommonBattleFinishModel battleFinishModel`

- `Boolean isInited`


## Methods

- `CommonBattleFinishModel get_battleFinishModel()`

- `Boolean get_isInited()`

- `Void LoadData(CommonFinishBattleResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHomeStateBean : SingletonMonoBehaviour`1, IStateBean, IHotfixable, IDataBindWrapper
{
	private CommonBattleFinishModel m_battleFinishModel; // 0x18
	private static DelegateBridge __Hotfix0_get_battleFinishModel; // 0x0
	private static DelegateBridge __Hotfix0_get_isInited; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_FindCharsInDropItems; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CommonBattleFinishModel battleFinishModel { get; }
	public Boolean isInited { get; }

	// RVA: 0x2e8b600 VA: 0x75954a3600
	public CommonBattleFinishModel get_battleFinishModel() { }
	// RVA: 0x2e8b668 VA: 0x75954a3668
	public Boolean get_isInited() { }
	// RVA: 0x2e8b6d8 VA: 0x75954a36d8
	public Void LoadData(CommonFinishBattleResponse response) { }
	// RVA: 0x2e8b760 VA: 0x75954a3760
	public List`1 FindCharsInDropItems() { }
	// RVA: 0x2e8b7d0 VA: 0x75954a37d0
	public Void .ctor() { }
}
```