# ClimbTowerInitGodDisplayModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 m_totalStepCount`

- `Int32 m_currentStep`

- `Int32 m_selectedIdx`

- `Boolean m_isHard`


## Properties

- `Int32 totalStepCount`

- `Int32 selectedIdx`

- `ClimbTowerInitGodCardModel selectedCardModel`

- `Int32 currentStep`

- `Boolean isHard`


## Methods

- `Int32 get_totalStepCount()`

- `Int32 get_selectedIdx()`

- `ClimbTowerInitGodCardModel get_selectedCardModel()`

- `Int32 get_currentStep()`

- `Boolean get_isHard()`

- `Void InitData(UIPage)`

- `Void SelectItem(Int32)`

- `Void _GenerateGodCardIdList(PlayerTower)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitGodDisplayModel : IHotfixable
{
	private List`1 m_godCardList; // 0x10
	private List`1 m_godCardIdList; // 0x18
	private Int32 m_totalStepCount; // 0x20
	private Int32 m_currentStep; // 0x24
	private Int32 m_selectedIdx; // 0x28
	private Boolean m_isHard; // 0x2c
	private static DelegateBridge __Hotfix0_get_totalStepCount; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedIdx; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedCardModel; // 0x10
	private static DelegateBridge __Hotfix0_get_currentStep; // 0x18
	private static DelegateBridge __Hotfix0_get_godCardList; // 0x20
	private static DelegateBridge __Hotfix0_get_isHard; // 0x28
	private static DelegateBridge __Hotfix0_InitData; // 0x30
	private static DelegateBridge __Hotfix0_SelectItem; // 0x38
	private static DelegateBridge __Hotfix0__GenerateGodCardIdList; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 totalStepCount { get; }
	public Int32 selectedIdx { get; }
	public ClimbTowerInitGodCardModel selectedCardModel { get; }
	public Int32 currentStep { get; }
	public List`1 godCardList { get; }
	public Boolean isHard { get; }

	// RVA: 0x2cab3fc VA: 0x75952c33fc
	public Int32 get_totalStepCount() { }
	// RVA: 0x2cab464 VA: 0x75952c3464
	public Int32 get_selectedIdx() { }
	// RVA: 0x2caa38c VA: 0x75952c238c
	public ClimbTowerInitGodCardModel get_selectedCardModel() { }
	// RVA: 0x2cab4cc VA: 0x75952c34cc
	public Int32 get_currentStep() { }
	// RVA: 0x2cab534 VA: 0x75952c3534
	public List`1 get_godCardList() { }
	// RVA: 0x2ca9ffc VA: 0x75952c1ffc
	public Boolean get_isHard() { }
	// RVA: 0x2ca94ac VA: 0x75952c14ac
	public Void InitData(UIPage page) { }
	// RVA: 0x2ca99dc VA: 0x75952c19dc
	public Void SelectItem(Int32 index) { }
	// RVA: 0x2cab59c VA: 0x75952c359c
	private Void _GenerateGodCardIdList(PlayerTower playerTower) { }
	// RVA: 0x2cab79c VA: 0x75952c379c
	public Void .ctor() { }
}
```