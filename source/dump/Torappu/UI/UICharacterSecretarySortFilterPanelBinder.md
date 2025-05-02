# UICharacterSecretarySortFilterPanelBinder

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _panelHolder`

- `UICharacterSecretarySortFilterPanel _panelPrefab`

- `RectTransform _transSortFilterBlocker`

- `CharacterFilterMessage _onFilterEvent`

- `Boolean m_isInited`

- `UICharacterSecretarySortFilterPanel m_sortFilterPanel`


## Methods

- `Void _InitIfNot()`

- `Void OnFilterBlockClick()`

- `Void <_InitIfNot>b__7_0(CharacterFilterViewModel)`

- `Void <_InitIfNot>b__7_1()`

- `Void <_InitIfNot>b__7_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSecretarySortFilterPanelBinder : DataBinder`1
{
	private RectTransform _panelHolder; // 0x20
	private UICharacterSecretarySortFilterPanel _panelPrefab; // 0x28
	private RectTransform _transSortFilterBlocker; // 0x30
	private CharacterFilterMessage _onFilterEvent; // 0x38
	private Boolean m_isInited; // 0x40
	private UICharacterSecretarySortFilterPanel m_sortFilterPanel; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnFilterBlockClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x21318a4 VA: 0x75947498a4
	public override Void OnValueChanged(HomeSecretaryChangeCardGroupViewProperty property) { }
	// RVA: 0x213195c VA: 0x759474995c
	private Void _InitIfNot() { }
	// RVA: 0x2131bf0 VA: 0x7594749bf0
	public Void OnFilterBlockClick() { }
	// RVA: 0x2131c60 VA: 0x7594749c60
	public Void .ctor() { }
	// RVA: 0x2131cf0 VA: 0x7594749cf0
	private Void <_InitIfNot>b__7_0(CharacterFilterViewModel filterModel) { }
	// RVA: 0x2131d50 VA: 0x7594749d50
	private Void <_InitIfNot>b__7_1() { }
	// RVA: 0x2131d78 VA: 0x7594749d78
	private Void <_InitIfNot>b__7_2() { }
}
```