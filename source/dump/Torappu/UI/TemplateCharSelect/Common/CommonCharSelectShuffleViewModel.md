# CommonCharSelectShuffleViewModel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `CharacterSortType m_sortType`

- `ProfessionCategory m_profFilter`

- `Boolean m_showFilterPanel`


## Properties

- `Boolean showFilterPanel`


## Methods

- `Boolean SetSortType(CharacterSortType)`

- `Boolean SetProfFilter(ProfessionCategory)`

- `Boolean get_showFilterPanel()`

- `Boolean SetFilterPanelVisible(Boolean)`

- `Void <>xLuaBaseProxy_OnReset(TemplateCharSelectModelResetData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectShuffleViewModel : TemplateShuffleViewModelBase`1
{
	private CharacterSortType m_sortType; // 0x10
	private ProfessionCategory m_profFilter; // 0x14
	private Boolean m_showFilterPanel; // 0x18
	private static DelegateBridge __Hotfix0_OnReset; // 0x0
	private static DelegateBridge __Hotfix0_get_sortType; // 0x8
	private static DelegateBridge __Hotfix0_SetSortType; // 0x10
	private static DelegateBridge __Hotfix0_get_profFilter; // 0x18
	private static DelegateBridge __Hotfix0_SetProfFilter; // 0x20
	private static DelegateBridge __Hotfix0_get_showFilterPanel; // 0x28
	private static DelegateBridge __Hotfix0_SetFilterPanelVisible; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override CharacterSortType sortType { get; }
	public override ProfessionCategory profFilter { get; }
	public Boolean showFilterPanel { get; }

	// RVA: 0x2c5c41c VA: 0x759527441c
	public override Void OnReset(TemplateCharSelectModelResetData data) { }
	// RVA: 0x2c5c4b0 VA: 0x75952744b0
	public override CharacterSortType get_sortType() { }
	// RVA: 0x2c5bc70 VA: 0x7595273c70
	public Boolean SetSortType(CharacterSortType st) { }
	// RVA: 0x2c5c518 VA: 0x7595274518
	public override ProfessionCategory get_profFilter() { }
	// RVA: 0x2c5b75c VA: 0x759527375c
	public Boolean SetProfFilter(ProfessionCategory profFilter) { }
	// RVA: 0x2c5b5bc VA: 0x75952735bc
	public Boolean get_showFilterPanel() { }
	// RVA: 0x2c5b97c VA: 0x759527397c
	public Boolean SetFilterPanelVisible(Boolean v) { }
	// RVA: 0x2c5c580 VA: 0x7595274580
	public Void .ctor() { }
	// RVA: 0x2c5c610 VA: 0x7595274610
	private Void <>xLuaBaseProxy_OnReset(TemplateCharSelectModelResetData P0) { }
}
```