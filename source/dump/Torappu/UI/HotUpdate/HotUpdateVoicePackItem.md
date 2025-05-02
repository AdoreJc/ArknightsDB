# HotUpdateVoicePackItem

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Image _imgBkg`

- `Text _textTitle`

- `Text _textDesc`

- `Text _textNotice`

- `ThreeStateToggle _toggle`

- `GameObject _objInvalid`

- `Color _colorSelectableTitle`

- `Color _colorNormal`

- `Color _colorSelectBkg`

- `Color _colorUnselectBkg`

- `String m_cachedResType`

- `Int32 m_cachedIndex`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(Options)`

- `Void _UpdateContent(String, Int64)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateVoicePackItem : MonoBehaviour, IHotfixable
{
	private Image _imgBkg; // 0x18
	private Text _textTitle; // 0x20
	private Text _textDesc; // 0x28
	private Text _textNotice; // 0x30
	private ThreeStateToggle _toggle; // 0x38
	private GameObject _objInvalid; // 0x40
	private Color _colorSelectableTitle; // 0x48
	private Color _colorNormal; // 0x58
	private Color _colorSelectBkg; // 0x68
	private Color _colorUnselectBkg; // 0x78
	private String m_cachedResType; // 0x88
	private Int32 m_cachedIndex; // 0x90
	private Action`1 <onClicked>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__UpdateContent; // 0x18
	private static DelegateBridge __Hotfix0__GetViewDataFromResType; // 0x20
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClicked { get; set; }

	// RVA: 0x27cea00 VA: 0x7594de6a00
	private Action`1 get_onClicked() { }
	// RVA: 0x27cea68 VA: 0x7594de6a68
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x27ceaec VA: 0x7594de6aec
	public Void Render(Options options) { }
	// RVA: 0x27cece8 VA: 0x7594de6ce8
	private Void _UpdateContent(String voiceResType, Int64 size) { }
	// RVA: 0x27ceedc VA: 0x7594de6edc
	private static ViewData _GetViewDataFromResType(String voiceResType) { }
	// RVA: 0x27cf1f4 VA: 0x7594de71f4
	public Void EventOnClick() { }
	// RVA: 0x27cf2ac VA: 0x7594de72ac
	public Void .ctor() { }
}
```