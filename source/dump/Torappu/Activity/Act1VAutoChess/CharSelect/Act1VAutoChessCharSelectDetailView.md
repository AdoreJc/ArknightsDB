# Act1VAutoChessCharSelectDetailView

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `Act1VAutoChessCharSelectDetailPanel _detailPanelPrefab`

- `Transform _detailContainer`

- `Act1VAutoChessCharSelectDetailPanel m_detailPanel`


## Methods

- `Void SwitchGold(Boolean)`

- `Void SelectSkill(String)`

- `Void SelectEquip(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectDetailView : TemplateCharSelectDetailViewBase`1, ICtrl
{
	private Act1VAutoChessCharSelectDetailPanel _detailPanelPrefab; // 0x30
	private Transform _detailContainer; // 0x38
	private Act1VAutoChessCharSelectDetailPanel m_detailPanel; // 0x40
	private static DelegateBridge __Hotfix0_OnRenderViewModel; // 0x0
	private static DelegateBridge __Hotfix0_SwitchGold; // 0x8
	private static DelegateBridge __Hotfix0_SelectSkill; // 0x10
	private static DelegateBridge __Hotfix0_SelectEquip; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x33888c4 VA: 0x75959a08c4
	protected override Void OnRenderViewModel() { }
	// RVA: 0x3388a00 VA: 0x75959a0a00
	public Void SwitchGold(Boolean isGold) { }
	// RVA: 0x3388c14 VA: 0x75959a0c14
	public Void SelectSkill(String skillId) { }
	// RVA: 0x3388ce8 VA: 0x75959a0ce8
	public Void SelectEquip(String equipId) { }
	// RVA: 0x3388dbc VA: 0x75959a0dbc
	public Void .ctor() { }
}
```