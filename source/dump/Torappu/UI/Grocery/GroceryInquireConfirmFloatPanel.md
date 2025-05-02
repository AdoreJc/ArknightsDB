# GroceryInquireConfirmFloatPanel

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `UIFadeFloatPanel _fadeFloatPanel`

- `Text _txtInquireInfo`

- `Text _txtInquireTips`

- `RectTransform _rectBackBtn`

- `Boolean m_hasInited`

- `String m_cachedGoodId`

- `String m_cachedShopId`

- `Boolean m_isDataValid`


## Properties

- `UIFadeFloatPanel fadeFloatPanel`


## Methods

- `UIFadeFloatPanel get_fadeFloatPanel()`

- `Void Render(ParamBase)`

- `Void EventOnCancelClicked()`

- `Void EventOnConfirmClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryInquireConfirmFloatPanel : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _fadeFloatPanel; // 0x18
	private Text _txtInquireInfo; // 0x20
	private Text _txtInquireTips; // 0x28
	private RectTransform _rectBackBtn; // 0x30
	private Boolean m_hasInited; // 0x38
	private String m_cachedGoodId; // 0x40
	private String m_cachedShopId; // 0x48
	private Boolean m_isDataValid; // 0x50
	private Action`2 m_onConfirm; // 0x58
	private static DelegateBridge __Hotfix0_get_fadeFloatPanel; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCancelClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UIFadeFloatPanel fadeFloatPanel { get; }

	// RVA: 0x286576c VA: 0x7594e7d76c
	public UIFadeFloatPanel get_fadeFloatPanel() { }
	// RVA: 0x28657d4 VA: 0x7594e7d7d4
	public Void Render(ParamBase input) { }
	// RVA: 0x2865a00 VA: 0x7594e7da00
	public Void EventOnCancelClicked() { }
	// RVA: 0x2865a74 VA: 0x7594e7da74
	public Void EventOnConfirmClicked() { }
	// RVA: 0x28658f0 VA: 0x7594e7d8f0
	private Void _InitIfNot() { }
	// RVA: 0x2865b18 VA: 0x7594e7db18
	public Void .ctor() { }
}
```