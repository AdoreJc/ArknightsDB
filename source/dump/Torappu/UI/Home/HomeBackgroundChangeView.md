# HomeBackgroundChangeView

**Namespace:** `Torappu.UI.Home`


## Fields

- `TwoStateToggle _sortToggle`

- `GameObject _objUnlockInfo`

- `Text _textUnlockBgName`

- `Text _textUnlockBgmName`

- `Text _textBgDes`

- `GameObject _objLockInfo`

- `Text _textLockBgName`

- `Text _textLockBgmName`

- `Text _textUnlockConditions`

- `HomeBackgroundListAdapter _homeBackgroundList`

- `Button _btnConfirm`

- `GameObject _objBtnConfirmBlocker`

- `TwoStateToggle _hideIllustToggle`

- `GameObject _checkPosBtnGroup`

- `Action onIllustHideChanged`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _OnSortToggleClick(State)`

- `Void _HandleBgSelectChanged(String)`

- `Void _RefreshSelectedInfo(HomeBackgroundItemModel, Boolean, Boolean)`

- `Void OnHideIllustToggle()`

- `Void InitToggle(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeBackgroundChangeView : DataBinder`1
{
	private TwoStateToggle _sortToggle; // 0x20
	private GameObject _objUnlockInfo; // 0x28
	private Text _textUnlockBgName; // 0x30
	private Text _textUnlockBgmName; // 0x38
	private Text _textBgDes; // 0x40
	private GameObject _objLockInfo; // 0x48
	private Text _textLockBgName; // 0x50
	private Text _textLockBgmName; // 0x58
	private Text _textUnlockConditions; // 0x60
	private HomeBackgroundListAdapter _homeBackgroundList; // 0x68
	private Button _btnConfirm; // 0x70
	private GameObject _objBtnConfirmBlocker; // 0x78
	private TwoStateToggle _hideIllustToggle; // 0x80
	private GameObject _checkPosBtnGroup; // 0x88
	public Action`1 onSortToggleClick; // 0x90
	public Action`1 onBgSelectChanged; // 0x98
	public Action onIllustHideChanged; // 0xa0
	private Boolean m_isInited; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__OnSortToggleClick; // 0x8
	private static DelegateBridge __Hotfix0__HandleBgSelectChanged; // 0x10
	private static DelegateBridge __Hotfix0__RefreshSelectedInfo; // 0x18
	private static DelegateBridge __Hotfix0_OnHideIllustToggle; // 0x20
	private static DelegateBridge __Hotfix0_InitToggle; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2835fc4 VA: 0x7594e4dfc4
	private Void _InitIfNot() { }
	// RVA: 0x2836168 VA: 0x7594e4e168
	private Void _OnSortToggleClick(State state) { }
	// RVA: 0x2836208 VA: 0x7594e4e208
	private Void _HandleBgSelectChanged(String bgId) { }
	// RVA: 0x28362a8 VA: 0x7594e4e2a8
	private Void _RefreshSelectedInfo(HomeBackgroundItemModel selected, Boolean hideIllustFlag, Boolean canCheckPos) { }
	// RVA: 0x2836910 VA: 0x7594e4e910
	public Void OnHideIllustToggle() { }
	// RVA: 0x2836994 VA: 0x7594e4e994
	public Void InitToggle(Boolean ascend) { }
	// RVA: 0x2836a24 VA: 0x7594e4ea24
	public override Void OnValueChanged(HomeBackgroundChangeViewProperty property) { }
	// RVA: 0x2836b28 VA: 0x7594e4eb28
	public Void .ctor() { }
}
```