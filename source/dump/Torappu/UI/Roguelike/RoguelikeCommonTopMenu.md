# RoguelikeCommonTopMenu

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _backButton`

- `RectTransform _returnButton`

- `RectTransform _infoButton`

- `Boolean m_isShowBackButton`

- `Boolean m_isShowReturnButton`

- `Boolean m_isShowInfoButton`

- `Action <onBackClicked>k__BackingField`

- `Action <onInfoClicked>k__BackingField`


## Properties

- `Action onBackClicked`

- `Action onInfoClicked`

- `Boolean isShowBackButton`

- `Boolean isShowReturnButton`

- `Boolean isShowInfoButton`


## Methods

- `Action get_onBackClicked()`

- `Void set_onBackClicked(Action)`

- `Action get_onInfoClicked()`

- `Void set_onInfoClicked(Action)`

- `Boolean get_isShowBackButton()`

- `Void set_isShowBackButton(Boolean)`

- `Boolean get_isShowReturnButton()`

- `Void set_isShowReturnButton(Boolean)`

- `Boolean get_isShowInfoButton()`

- `Void set_isShowInfoButton(Boolean)`

- `Void EventOnBackClicked()`

- `Void EventOnCloseClicked()`

- `Void EventOnInfoClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCommonTopMenu : MonoBehaviour, IHotfixable
{
	private RectTransform _backButton; // 0x18
	private RectTransform _returnButton; // 0x20
	private RectTransform _infoButton; // 0x28
	private Boolean m_isShowBackButton; // 0x30
	private Boolean m_isShowReturnButton; // 0x31
	private Boolean m_isShowInfoButton; // 0x32
	private Action <onBackClicked>k__BackingField; // 0x38
	private Action <onInfoClicked>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onBackClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onBackClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onInfoClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onInfoClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_isShowBackButton; // 0x20
	private static DelegateBridge __Hotfix0_set_isShowBackButton; // 0x28
	private static DelegateBridge __Hotfix0_get_isShowReturnButton; // 0x30
	private static DelegateBridge __Hotfix0_set_isShowReturnButton; // 0x38
	private static DelegateBridge __Hotfix0_get_isShowInfoButton; // 0x40
	private static DelegateBridge __Hotfix0_set_isShowInfoButton; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnCloseClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnInfoClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public Action onBackClicked { get; set; }
	public Action onInfoClicked { get; set; }
	public Boolean isShowBackButton { get; set; }
	public Boolean isShowReturnButton { get; set; }
	public Boolean isShowInfoButton { get; set; }

	// RVA: 0x29f4bec VA: 0x759500cbec
	public Action get_onBackClicked() { }
	// RVA: 0x29f4c54 VA: 0x759500cc54
	public Void set_onBackClicked(Action value) { }
	// RVA: 0x29f4cd8 VA: 0x759500ccd8
	public Action get_onInfoClicked() { }
	// RVA: 0x29f4d40 VA: 0x759500cd40
	public Void set_onInfoClicked(Action value) { }
	// RVA: 0x29f4dc4 VA: 0x759500cdc4
	public Boolean get_isShowBackButton() { }
	// RVA: 0x29f4e2c VA: 0x759500ce2c
	public Void set_isShowBackButton(Boolean value) { }
	// RVA: 0x29f4ee8 VA: 0x759500cee8
	public Boolean get_isShowReturnButton() { }
	// RVA: 0x29f4f50 VA: 0x759500cf50
	public Void set_isShowReturnButton(Boolean value) { }
	// RVA: 0x29f500c VA: 0x759500d00c
	public Boolean get_isShowInfoButton() { }
	// RVA: 0x29f5074 VA: 0x759500d074
	public Void set_isShowInfoButton(Boolean value) { }
	// RVA: 0x29f5130 VA: 0x759500d130
	public Void EventOnBackClicked() { }
	// RVA: 0x29f51cc VA: 0x759500d1cc
	public Void EventOnCloseClicked() { }
	// RVA: 0x29f52c4 VA: 0x759500d2c4
	public Void EventOnInfoClicked() { }
	// RVA: 0x29f5360 VA: 0x759500d360
	public Void .ctor() { }
}
```