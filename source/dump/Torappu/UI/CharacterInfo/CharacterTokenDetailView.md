# CharacterTokenDetailView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `UIFadeFloatPanel _floatPanel`

- `ScrollRect _scrollRect`

- `RectTransform _closeBtn`

- `CharacterTokenDetailShowView _showView`

- `GameObject _noInfoObj`

- `Boolean m_isInited`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void Render(CharTokenViewModel)`

- `Void _InitIfNot()`

- `Void _ShowPanelView()`

- `Void EventOnHideView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterTokenDetailView : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _floatPanel; // 0x18
	private ScrollRect _scrollRect; // 0x20
	private RectTransform _closeBtn; // 0x28
	private CharacterTokenDetailShowView _showView; // 0x30
	private GameObject _noInfoObj; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ShowPanelView; // 0x18
	private static DelegateBridge __Hotfix0_EventOnHideView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isShow { get; }

	// RVA: 0x2d6aa8c VA: 0x7595382a8c
	public Boolean get_isShow() { }
	// RVA: 0x2d6ab00 VA: 0x7595382b00
	public Void Render(CharTokenViewModel tokenData) { }
	// RVA: 0x2d6abc4 VA: 0x7595382bc4
	private Void _InitIfNot() { }
	// RVA: 0x2d6acd4 VA: 0x7595382cd4
	private Void _ShowPanelView() { }
	// RVA: 0x2d6ad6c VA: 0x7595382d6c
	public Void EventOnHideView() { }
	// RVA: 0x2d6ade0 VA: 0x7595382de0
	public Void .ctor() { }
}
```