# UICharacterRepoSortFilterPanelBinder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _panelHolder`

- `UICharacterSortFilterPanel _panelPrefab`

- `CharacterFilterMessage _onFilterEvent`

- `CharacterSortTypeMessage _onSortEvent`

- `Boolean m_isInited`

- `UICharacterSortFilterPanel m_sortFilterPanel`

- `Boolean m_itemBind`

- `IntProperty m_charHandbookStageCntProperty`

- `String pageName`


## Methods

- `Void _InitIfNot()`

- `Void _BindCntItemIfNot()`

- `Void onSortPanelShow()`

- `Void OnFilterPanelShow()`

- `Void OnFilterPanelHide()`

- `Void OnFilterPanelSwitch(Boolean)`

- `Void <_InitIfNot>b__10_0(CharacterFilterViewModel)`

- `Void <_InitIfNot>b__10_1(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterRepoSortFilterPanelBinder : DataBinder`1, IHotfixable
{
	private RectTransform _panelHolder; // 0x20
	private UICharacterSortFilterPanel _panelPrefab; // 0x28
	private CharacterFilterMessage _onFilterEvent; // 0x30
	private CharacterSortTypeMessage _onSortEvent; // 0x38
	private Boolean m_isInited; // 0x40
	private UICharacterSortFilterPanel m_sortFilterPanel; // 0x48
	private Boolean m_itemBind; // 0x50
	private IntProperty m_charHandbookStageCntProperty; // 0x58
	public String pageName; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__BindCntItemIfNot; // 0x10
	private static DelegateBridge __Hotfix0_onSortPanelShow; // 0x18
	private static DelegateBridge __Hotfix0_OnFilterPanelShow; // 0x20
	private static DelegateBridge __Hotfix0_OnFilterPanelHide; // 0x28
	private static DelegateBridge __Hotfix0_OnFilterPanelSwitch; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x21304b4 VA: 0x75947484b4
	public override Void OnValueChanged(CharacterRepoCardGroupViewProperty property) { }
	// RVA: 0x21305e8 VA: 0x75947485e8
	private Void _InitIfNot() { }
	// RVA: 0x213087c VA: 0x759474887c
	private Void _BindCntItemIfNot() { }
	// RVA: 0x2130aac VA: 0x7594748aac
	public Void onSortPanelShow() { }
	// RVA: 0x2130c20 VA: 0x7594748c20
	public Void OnFilterPanelShow() { }
	// RVA: 0x2130d74 VA: 0x7594748d74
	public Void OnFilterPanelHide() { }
	// RVA: 0x21309ac VA: 0x75947489ac
	public Void OnFilterPanelSwitch(Boolean isShow) { }
	// RVA: 0x2130ec8 VA: 0x7594748ec8
	public Void .ctor() { }
	// RVA: 0x2130f98 VA: 0x7594748f98
	private Void <_InitIfNot>b__10_0(CharacterFilterViewModel filterModel) { }
	// RVA: 0x2130ff8 VA: 0x7594748ff8
	private Void <_InitIfNot>b__10_1(CharacterSortType sortType) { }
}
```