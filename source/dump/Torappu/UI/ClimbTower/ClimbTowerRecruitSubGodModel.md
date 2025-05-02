# ClimbTowerRecruitSubGodModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerMainCardData m_mainCardData`

- `String m_selectSubId`

- `String m_towerId`

- `Int32 m_currentFloor`


## Properties

- `String selectedSubId`

- `Boolean haveSubSelected`

- `String towerId`

- `String mainCardName`

- `Int32 currentFloor`


## Methods

- `String get_selectedSubId()`

- `Boolean get_haveSubSelected()`

- `String get_towerId()`

- `String get_mainCardName()`

- `Int32 get_currentFloor()`

- `Void LoadData(UIPage)`

- `Void SelectSubCard(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRecruitSubGodModel : IHotfixable
{
	private List`1 m_subItemList; // 0x10
	private ClimbTowerMainCardData m_mainCardData; // 0x18
	private String m_selectSubId; // 0x20
	private String m_towerId; // 0x28
	private Int32 m_currentFloor; // 0x30
	private static DelegateBridge __Hotfix0_get_selectedSubId; // 0x0
	private static DelegateBridge __Hotfix0_get_haveSubSelected; // 0x8
	private static DelegateBridge __Hotfix0_get_towerId; // 0x10
	private static DelegateBridge __Hotfix0_get_mainCardName; // 0x18
	private static DelegateBridge __Hotfix0_get_currentFloor; // 0x20
	private static DelegateBridge __Hotfix0_get_subCardList; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_SelectSubCard; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String selectedSubId { get; }
	public Boolean haveSubSelected { get; }
	public String towerId { get; }
	public String mainCardName { get; }
	public Int32 currentFloor { get; }
	public List`1 subCardList { get; }

	// RVA: 0x2cad844 VA: 0x75952c5844
	public String get_selectedSubId() { }
	// RVA: 0x2cadd28 VA: 0x75952c5d28
	public Boolean get_haveSubSelected() { }
	// RVA: 0x2cad0e4 VA: 0x75952c50e4
	public String get_towerId() { }
	// RVA: 0x2cadda0 VA: 0x75952c5da0
	public String get_mainCardName() { }
	// RVA: 0x2cade34 VA: 0x75952c5e34
	public Int32 get_currentFloor() { }
	// RVA: 0x2cade9c VA: 0x75952c5e9c
	public List`1 get_subCardList() { }
	// RVA: 0x2cacd90 VA: 0x75952c4d90
	public Void LoadData(UIPage page) { }
	// RVA: 0x2cad2b0 VA: 0x75952c52b0
	public Void SelectSubCard(String subCardId) { }
	// RVA: 0x2cadf04 VA: 0x75952c5f04
	public Void .ctor() { }
}
```