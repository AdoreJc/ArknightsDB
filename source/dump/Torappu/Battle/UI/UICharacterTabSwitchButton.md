# UICharacterTabSwitchButton

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _splitImage`

- `CanvasGroup _displayedPanel`

- `Image _highlightTriangleGraphic`

- `Image _highlightGraphic`

- `Text _titleText`

- `Color _textHideColor`

- `Color _textShowColor`

- `TabInfomationStyleEnum _buttonType`


## Properties

- `TabInfomationStyleEnum buttonType`

- `Image splitImage`


## Methods

- `TabInfomationStyleEnum get_buttonType()`

- `Void set_onTabClicked(Action`1)`

- `Image get_splitImage()`

- `Void Show()`

- `Void Hide()`

- `Void EventOnTabClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterTabSwitchButton : MonoBehaviour, IHotfixable
{
	private Image _splitImage; // 0x18
	private CanvasGroup _displayedPanel; // 0x20
	private Image _highlightTriangleGraphic; // 0x28
	private Image _highlightGraphic; // 0x30
	private Text _titleText; // 0x38
	private Color _textHideColor; // 0x40
	private Color _textShowColor; // 0x50
	private TabInfomationStyleEnum _buttonType; // 0x60
	private Action`1 <onTabClicked>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_buttonType; // 0x0
	private static DelegateBridge __Hotfix0_get_onTabClicked; // 0x8
	private static DelegateBridge __Hotfix0_set_onTabClicked; // 0x10
	private static DelegateBridge __Hotfix0_get_splitImage; // 0x18
	private static DelegateBridge __Hotfix0_Show; // 0x20
	private static DelegateBridge __Hotfix0_Hide; // 0x28
	private static DelegateBridge __Hotfix0_EventOnTabClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public TabInfomationStyleEnum buttonType { get; }
	private Action`1 onTabClicked { get; set; }
	public Image splitImage { get; }

	// RVA: 0x203ab40 VA: 0x7594652b40
	public TabInfomationStyleEnum get_buttonType() { }
	// RVA: 0x203b578 VA: 0x7594653578
	private Action`1 get_onTabClicked() { }
	// RVA: 0x203aabc VA: 0x7594652abc
	public Void set_onTabClicked(Action`1 value) { }
	// RVA: 0x203b5e0 VA: 0x75946535e0
	public Image get_splitImage() { }
	// RVA: 0x203aba8 VA: 0x7594652ba8
	public Void Show() { }
	// RVA: 0x203ac80 VA: 0x7594652c80
	public Void Hide() { }
	// RVA: 0x203b648 VA: 0x7594653648
	public Void EventOnTabClicked() { }
	// RVA: 0x203b6e8 VA: 0x75946536e8
	public Void .ctor() { }
}
```