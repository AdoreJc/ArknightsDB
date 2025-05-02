# UICharacterSecretarySortFilterPanel

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _objFilterAll`

- `GameObject _objFilterOther`

- `Text _txtFilterOther`

- `TwoStateToggle _toggleCurFilter`

- `UICharacterFilterGroupOnFloat _filterGroup`

- `CanvasGroup _filterPanel`

- `Action eventOnFilterFadeIn`

- `Action eventOnFilterFadeOut`

- `Boolean m_isInited`

- `Tweener m_fadeIn`

- `Tweener m_fadeOut`

- `Boolean m_filterShowing`


## Methods

- `Void Render(CharacterFilterViewModel)`

- `Void EventOnBackClick()`

- `Void _InitIfNot()`

- `Void _OnToggleClick(State)`

- `Void _UpdateProfessionStr(CharacterFilterViewModel)`

- `Void _EventOnFilterClick(CharacterFilterViewModel)`

- `Void _EventOnFadeOutFilter()`

- `Void _EventOnFadeInFilter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterSecretarySortFilterPanel : MonoBehaviour, IHotfixable
{
	private GameObject _objFilterAll; // 0x18
	private GameObject _objFilterOther; // 0x20
	private Text _txtFilterOther; // 0x28
	private TwoStateToggle _toggleCurFilter; // 0x30
	private UICharacterFilterGroupOnFloat _filterGroup; // 0x38
	private CanvasGroup _filterPanel; // 0x40
	public Action`1 eventOnFilterClick; // 0x48
	public Action eventOnFilterFadeIn; // 0x50
	public Action eventOnFilterFadeOut; // 0x58
	private Boolean m_isInited; // 0x60
	private Tweener m_fadeIn; // 0x68
	private Tweener m_fadeOut; // 0x70
	private Boolean m_filterShowing; // 0x78
	private const Single FAST_TWEEN_DUR; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnToggleClick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateProfessionStr; // 0x20
	private static DelegateBridge __Hotfix0__EventOnFilterClick; // 0x28
	private static DelegateBridge __Hotfix0__EventOnFadeOutFilter; // 0x30
	private static DelegateBridge __Hotfix0__EventOnFadeInFilter; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2131058 VA: 0x7594749058
	public Void Render(CharacterFilterViewModel filter) { }
	// RVA: 0x2131430 VA: 0x7594749430
	public Void EventOnBackClick() { }
	// RVA: 0x21310f4 VA: 0x75947490f4
	private Void _InitIfNot() { }
	// RVA: 0x21315a8 VA: 0x75947495a8
	private Void _OnToggleClick(State state) { }
	// RVA: 0x21312c0 VA: 0x75947492c0
	private Void _UpdateProfessionStr(CharacterFilterViewModel viewModel) { }
	// RVA: 0x2131724 VA: 0x7594749724
	private Void _EventOnFilterClick(CharacterFilterViewModel viewModel) { }
	// RVA: 0x21314c4 VA: 0x75947494c4
	private Void _EventOnFadeOutFilter() { }
	// RVA: 0x213163c VA: 0x759474963c
	private Void _EventOnFadeInFilter() { }
	// RVA: 0x21317ec VA: 0x75947497ec
	public Void .ctor() { }
}
```