# UICharacterSortFilterPanelBinder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _panelHolder`

- `UICharacterSortFilterPanel _panelPrefab`

- `CharacterFilterMessage _onFilterEvent`

- `CharacterSortTypeMessage _onSortEvent`

- `String pageName`

- `Boolean m_isInited`

- `UICharacterSortFilterPanel m_sortFilterPanel`


## Methods

- `Void _InitIfNot()`

- `Void onSortPanelShow()`

- `Void OnFilterPanelShow()`

- `Void OnFilterPanelHide()`

- `Void OnFilterPanelSwitch(Boolean)`

- `Void <_InitIfNot>b__8_0(CharacterFilterViewModel)`

- `Void <_InitIfNot>b__8_1(CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSortFilterPanelBinder : DataBinder`1, IHotfixable
{
	private RectTransform _panelHolder; // 0x20
	private UICharacterSortFilterPanel _panelPrefab; // 0x28
	private CharacterFilterMessage _onFilterEvent; // 0x30
	private CharacterSortTypeMessage _onSortEvent; // 0x38
	public String pageName; // 0x40
	private Boolean m_isInited; // 0x48
	private UICharacterSortFilterPanel m_sortFilterPanel; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_onSortPanelShow; // 0x10
	private static DelegateBridge __Hotfix0_OnFilterPanelShow; // 0x18
	private static DelegateBridge __Hotfix0_OnFilterPanelHide; // 0x20
	private static DelegateBridge __Hotfix0_OnFilterPanelSwitch; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21323dc VA: 0x759474a3dc
	public override Void OnValueChanged(CardGroupViewProperty property) { }
	// RVA: 0x21324b8 VA: 0x759474a4b8
	private Void _InitIfNot() { }
	// RVA: 0x213270c VA: 0x759474a70c
	public Void onSortPanelShow() { }
	// RVA: 0x21327c4 VA: 0x759474a7c4
	public Void OnFilterPanelShow() { }
	// RVA: 0x213287c VA: 0x759474a87c
	public Void OnFilterPanelHide() { }
	// RVA: 0x213267c VA: 0x759474a67c
	public Void OnFilterPanelSwitch(Boolean isShow) { }
	// RVA: 0x2132934 VA: 0x759474a934
	public Void .ctor() { }
	// RVA: 0x21329c4 VA: 0x759474a9c4
	private Void <_InitIfNot>b__8_0(CharacterFilterViewModel filterModel) { }
	// RVA: 0x2132a24 VA: 0x759474aa24
	private Void <_InitIfNot>b__8_1(CharacterSortType sortType) { }
}
```