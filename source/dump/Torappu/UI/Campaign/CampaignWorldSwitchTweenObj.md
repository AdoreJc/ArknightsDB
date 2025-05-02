# CampaignWorldSwitchTweenObj

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `CanvasGroup _canvasGroup`

- `RectTransform _rectTrans`

- `Vector2 _hidePos`

- `Vector2 _showPos`

- `Boolean _isShowOnStart`

- `Single duration`

- `Boolean m_inited`

- `FadeTranslationSwitchTween m_switchTween`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Void _InitIfNot()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldSwitchTweenObj : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasGroup; // 0x18
	private RectTransform _rectTrans; // 0x20
	private Vector2 _hidePos; // 0x28
	private Vector2 _showPos; // 0x30
	private Boolean _isShowOnStart; // 0x38
	private Single duration; // 0x3c
	private Boolean m_inited; // 0x40
	private FadeTranslationSwitchTween m_switchTween; // 0x48
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isShow; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isShow { get; set; }

	// RVA: 0x2ddab30 VA: 0x75953f2b30
	public Boolean get_isShow() { }
	// RVA: 0x2dd3fe0 VA: 0x75953ebfe0
	public Void set_isShow(Boolean value) { }
	// RVA: 0x2ddabac VA: 0x75953f2bac
	private Void _InitIfNot() { }
	// RVA: 0x2ddacdc VA: 0x75953f2cdc
	public Void Start() { }
	// RVA: 0x2ddad5c VA: 0x75953f2d5c
	public Void .ctor() { }
}
```