# HomeSecretarySkinChangeView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _txtSelectedRealName`

- `Text _txtSelectedNickName`

- `HomeSecretarySkinChangeGridAdapter _adapter`

- `LoopVerticalScrollRect _scrollRect`

- `Text _selectedSkinNum`

- `Image _skinGroupIcon`

- `Image _selectedSkinBg`

- `Color _selectedSkinSafeBgColor`

- `Color _selectedSkinDangerBgColor`

- `Text _selectedCharNum`

- `GameObject _skinGroupBg`

- `GameObject _selectCharBtn`

- `HomeSecretarySkinChangeViewModel m_viewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnConfirmClicked()`

- `Void OnCancelClicked()`

- `Void OnCleanAllClicked()`

- `Void OpenSelectCharState()`

- `Void OnEditIllustClicked()`

- `Void ResetListToTop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinChangeView : DataBinder`1
{
	private const String SELECTED_CHAR_FORMAT; // 0x0
	private Text _txtSelectedRealName; // 0x20
	private Text _txtSelectedNickName; // 0x28
	private HomeSecretarySkinChangeGridAdapter _adapter; // 0x30
	private LoopVerticalScrollRect _scrollRect; // 0x38
	private Text _selectedSkinNum; // 0x40
	private Image _skinGroupIcon; // 0x48
	private Image _selectedSkinBg; // 0x50
	private Color _selectedSkinSafeBgColor; // 0x58
	private Color _selectedSkinDangerBgColor; // 0x68
	private HomeSecretarySkinFilterItemView[] _filters; // 0x78
	private Text _selectedCharNum; // 0x80
	private GameObject _skinGroupBg; // 0x88
	private GameObject _selectCharBtn; // 0x90
	private HomeSecretarySkinChangeViewModel m_viewModel; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnCancelClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnCleanAllClicked; // 0x18
	private static DelegateBridge __Hotfix0_OpenSelectCharState; // 0x20
	private static DelegateBridge __Hotfix0_OnEditIllustClicked; // 0x28
	private static DelegateBridge __Hotfix0_ResetListToTop; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x283eeec VA: 0x7594e56eec
	public override Void OnValueChanged(HomeSecretarySkinChangeViewProperty property) { }
	// RVA: 0x283f440 VA: 0x7594e57440
	public Void OnConfirmClicked() { }
	// RVA: 0x283f4e4 VA: 0x7594e574e4
	public Void OnCancelClicked() { }
	// RVA: 0x283f588 VA: 0x7594e57588
	public Void OnCleanAllClicked() { }
	// RVA: 0x283f62c VA: 0x7594e5762c
	public Void OpenSelectCharState() { }
	// RVA: 0x283f6d0 VA: 0x7594e576d0
	public Void OnEditIllustClicked() { }
	// RVA: 0x283f774 VA: 0x7594e57774
	public Void ResetListToTop() { }
	// RVA: 0x283f7ec VA: 0x7594e577ec
	public Void .ctor() { }
}
```