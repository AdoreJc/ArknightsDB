# BirthdaySettingView

**Namespace:** `Torappu.UI.Birthday`


## Fields

- `Text _name`

- `Text _desc`

- `Text _date`

- `GameObject _panelSetStartDay`

- `GameObject _panelIsStartDay`

- `GameObject _panelConfirm`

- `GameObject _panelCannotConfirm`

- `Color _validDateColor`

- `Color _invalidDateColor`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnConfirm()`

- `Void OnSetDate()`

- `Void OnSetRegisterDate()`

- `Void OnCloseClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Birthday
public class BirthdaySettingView : DataBinder`1
{
	private Text _name; // 0x20
	private Text _desc; // 0x28
	private Text _date; // 0x30
	private GameObject _panelSetStartDay; // 0x38
	private GameObject _panelIsStartDay; // 0x40
	private GameObject _panelConfirm; // 0x48
	private GameObject _panelCannotConfirm; // 0x50
	private Color _validDateColor; // 0x58
	private Color _invalidDateColor; // 0x68
	private UIStateFinder m_stateFinder; // 0x78
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x8
	private static DelegateBridge __Hotfix0_OnSetDate; // 0x10
	private static DelegateBridge __Hotfix0_OnSetRegisterDate; // 0x18
	private static DelegateBridge __Hotfix0_OnCloseClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2e7e4a8 VA: 0x75954964a8
	public override Void OnValueChanged(BirthdaySettingProperty property) { }
	// RVA: 0x2e7e758 VA: 0x7595496758
	public Void OnConfirm() { }
	// RVA: 0x2e7e80c VA: 0x759549680c
	public Void OnSetDate() { }
	// RVA: 0x2e7e8c0 VA: 0x75954968c0
	public Void OnSetRegisterDate() { }
	// RVA: 0x2e7e974 VA: 0x7595496974
	public Void OnCloseClick() { }
	// RVA: 0x2e7ea28 VA: 0x7595496a28
	public Void .ctor() { }
}
```