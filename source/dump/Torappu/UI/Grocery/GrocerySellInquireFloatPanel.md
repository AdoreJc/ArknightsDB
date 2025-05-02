# GrocerySellInquireFloatPanel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `UIFadeFloatPanel _fadeFloatPanel`

- `Text _textTitle`

- `Text _textDesc`

- `SimpleLayoutContent _content`

- `RectTransform _rectBackBtn`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Properties

- `UIFadeFloatPanel fadeFloatPanel`


## Methods

- `UIFadeFloatPanel get_fadeFloatPanel()`

- `Void Render(String)`

- `Void EventOnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellInquireFloatPanel : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _fadeFloatPanel; // 0x18
	private Text _textTitle; // 0x20
	private Text _textDesc; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private RectTransform _rectBackBtn; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private List`1 m_cachedInquireList; // 0x50
	private static DelegateBridge __Hotfix0_get_fadeFloatPanel; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIFadeFloatPanel fadeFloatPanel { get; }

	// RVA: 0x288c2a8 VA: 0x7594ea42a8
	public UIFadeFloatPanel get_fadeFloatPanel() { }
	// RVA: 0x288c160 VA: 0x7594ea4160
	public Void Render(String actId) { }
	// RVA: 0x2898b80 VA: 0x7594eb0b80
	public Void EventOnClicked() { }
	// RVA: 0x2898a20 VA: 0x7594eb0a20
	private Void _InitIfNot() { }
	// RVA: 0x2898c88 VA: 0x7594eb0c88
	public Void .ctor() { }
}
```