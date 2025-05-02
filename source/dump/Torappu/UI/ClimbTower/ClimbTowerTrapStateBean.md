# ClimbTowerTrapStateBean

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String m_seaonId`

- `Boolean m_showBuffBtn`

- `Boolean m_showSquadBtn`

- `Boolean m_showProfessionBtns`


## Properties

- `String seasonId`

- `Boolean showBuffBtn`

- `Boolean showSquadBtn`

- `Boolean showProfessionBtns`


## Methods

- `String get_seasonId()`

- `Boolean get_showBuffBtn()`

- `Boolean get_showSquadBtn()`

- `Boolean get_showProfessionBtns()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrapStateBean : IStateBean, IHotfixable
{
	private List`1 m_groupViewModels; // 0x10
	private String m_seaonId; // 0x18
	private Boolean m_showBuffBtn; // 0x20
	private Boolean m_showSquadBtn; // 0x21
	private Boolean m_showProfessionBtns; // 0x22
	private static DelegateBridge __Hotfix0_get_seasonId; // 0x0
	private static DelegateBridge __Hotfix0_get_groupViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_showBuffBtn; // 0x10
	private static DelegateBridge __Hotfix0_get_showSquadBtn; // 0x18
	private static DelegateBridge __Hotfix0_get_showProfessionBtns; // 0x20
	private static DelegateBridge __Hotfix0_InitData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String seasonId { get; }
	public List`1 groupViewModels { get; }
	public Boolean showBuffBtn { get; }
	public Boolean showSquadBtn { get; }
	public Boolean showProfessionBtns { get; }

	// RVA: 0x2c903dc VA: 0x75952a83dc
	public String get_seasonId() { }
	// RVA: 0x2c9019c VA: 0x75952a819c
	public List`1 get_groupViewModels() { }
	// RVA: 0x2c8fac0 VA: 0x75952a7ac0
	public Boolean get_showBuffBtn() { }
	// RVA: 0x2c8fb98 VA: 0x75952a7b98
	public Boolean get_showSquadBtn() { }
	// RVA: 0x2c8fc70 VA: 0x75952a7c70
	public Boolean get_showProfessionBtns() { }
	// RVA: 0x2c8f40c VA: 0x75952a740c
	public Void InitData() { }
	// RVA: 0x2c8fdec VA: 0x75952a7dec
	public Void .ctor() { }
}
```