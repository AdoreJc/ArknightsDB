# EnemyHandBookStateBean

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `EnemyHandBookShowProperty m_property`

- `Int32 overrideSelectIdx`


## Properties

- `EnemyHandBookShowProperty property`


## Methods

- `EnemyHandBookShowProperty get_property()`

- `Void SetBossShuffle(EnemyLevelMask)`

- `Void SetRaceShuffle(Int32)`

- `Void SetMotionType(Int32)`

- `Void SetAttackType(Int32)`

- `Void SetDamageType(Int32)`

- `Void SetIncreaseType()`

- `Void CleanSelect()`

- `Void InitIndexAndShowState()`

- `Void SelectFirstNewIdx()`

- `Void LoadDataFromStageId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private EnemyHandBookShowProperty m_property; // 0x18
	public Int32 overrideSelectIdx; // 0x20
	private static DelegateBridge __Hotfix0_get_property; // 0x0
	private static DelegateBridge __Hotfix0_SetBossShuffle; // 0x8
	private static DelegateBridge __Hotfix0_SetRaceShuffle; // 0x10
	private static DelegateBridge __Hotfix0_SetMotionType; // 0x18
	private static DelegateBridge __Hotfix0_SetAttackType; // 0x20
	private static DelegateBridge __Hotfix0_SetDamageType; // 0x28
	private static DelegateBridge __Hotfix0_SetIncreaseType; // 0x30
	private static DelegateBridge __Hotfix0_CleanSelect; // 0x38
	private static DelegateBridge __Hotfix0_InitIndexAndShowState; // 0x40
	private static DelegateBridge __Hotfix0_SelectFirstNewIdx; // 0x48
	private static DelegateBridge __Hotfix0_LoadDataFromStageId; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public EnemyHandBookShowProperty property { get; }

	// RVA: 0x293c1e0 VA: 0x7594f541e0
	public EnemyHandBookShowProperty get_property() { }
	// RVA: 0x293c81c VA: 0x7594f5481c
	public Void SetBossShuffle(EnemyLevelMask type) { }
	// RVA: 0x293c900 VA: 0x7594f54900
	public Void SetRaceShuffle(Int32 index) { }
	// RVA: 0x293ca34 VA: 0x7594f54a34
	public Void SetMotionType(Int32 index) { }
	// RVA: 0x293cb68 VA: 0x7594f54b68
	public Void SetAttackType(Int32 index) { }
	// RVA: 0x293cc9c VA: 0x7594f54c9c
	public Void SetDamageType(Int32 index) { }
	// RVA: 0x293cdd0 VA: 0x7594f54dd0
	public Void SetIncreaseType() { }
	// RVA: 0x293ce9c VA: 0x7594f54e9c
	public Void CleanSelect() { }
	// RVA: 0x293c4c4 VA: 0x7594f544c4
	public Void InitIndexAndShowState() { }
	// RVA: 0x293cf58 VA: 0x7594f54f58
	public Void SelectFirstNewIdx() { }
	// RVA: 0x293cfe0 VA: 0x7594f54fe0
	public Void LoadDataFromStageId(String stageId) { }
	// RVA: 0x293d560 VA: 0x7594f55560
	public Void .ctor() { }
}
```