# HomeThemeChangeView

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeThemeListAdapter _adapter`

- `TwoStateToggle _sortToggle`

- `GameObject _objUnlockInfo`

- `Text _textUnlockThemeName`

- `Text _textThemeDes`

- `GameObject _objLockInfo`

- `Text _textLockThemeName`

- `Text _textUnlockConditions`

- `Button _btnConfirm`

- `GameObject _objBtnConfirmBlocker`

- `TwoStateToggle _hideIllustToggle`

- `Int32 m_routedSequenceNum`


## Methods

- `Void _RenderUnlockCondition(HomeThemeItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeThemeChangeView : DataBinder`1
{
	private HomeThemeListAdapter _adapter; // 0x20
	private TwoStateToggle _sortToggle; // 0x28
	private GameObject _objUnlockInfo; // 0x30
	private Text _textUnlockThemeName; // 0x38
	private Text _textThemeDes; // 0x40
	private GameObject _objLockInfo; // 0x48
	private Text _textLockThemeName; // 0x50
	private Text _textUnlockConditions; // 0x58
	private Button _btnConfirm; // 0x60
	private GameObject _objBtnConfirmBlocker; // 0x68
	private TwoStateToggle _hideIllustToggle; // 0x70
	public Action`1 onSortToggleClick; // 0x78
	public Action`1 onSelectChanged; // 0x80
	private const String UNLCOK_CONDITION_TYPE; // 0x0
	private Int32 m_routedSequenceNum; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderUnlockCondition; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x283fb9c VA: 0x7594e57b9c
	public override Void OnValueChanged(HomeThemeChangeViewProperty property) { }
	// RVA: 0x283ffa8 VA: 0x7594e57fa8
	private Void _RenderUnlockCondition(HomeThemeItemModel selected) { }
	// RVA: 0x28404a4 VA: 0x7594e584a4
	public Void .ctor() { }
}
```