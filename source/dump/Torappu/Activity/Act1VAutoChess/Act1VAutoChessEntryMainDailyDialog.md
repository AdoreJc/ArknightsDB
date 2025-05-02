# Act1VAutoChessEntryMainDailyDialog

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _progCurText`

- `Text _progMaxText`

- `Text _ruleDescText`

- `Text _titleText`

- `Slider _progSlider`

- `GameObject _progSliderFillObj`

- `UIRenderTextureImage _blurImg`

- `RectTransform _backPressRect`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClick()`

- `UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryMainDailyDialog : UICompDialog`1
{
	private Text _progCurText; // 0x48
	private Text _progMaxText; // 0x50
	private Text _ruleDescText; // 0x58
	private Text _titleText; // 0x60
	private Slider _progSlider; // 0x68
	private GameObject _progSliderFillObj; // 0x70
	private UIRenderTextureImage _blurImg; // 0x78
	private RectTransform _backPressRect; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_GetBlurTarget; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x333f610 VA: 0x7595957610
	private Void _InitIfNot() { }
	// RVA: 0x333f714 VA: 0x7595957714
	protected override Void OnRender(Option input) { }
	// RVA: 0x333f964 VA: 0x7595957964
	protected override UIRenderTextureImage GetBlurTarget() { }
	// RVA: 0x333f9cc VA: 0x75959579cc
	public Void EventOnClick() { }
	// RVA: 0x333faa0 VA: 0x7595957aa0
	public Void .ctor() { }
	// RVA: 0x333fb30 VA: 0x7595957b30
	private UIRenderTextureImage <>xLuaBaseProxy_GetBlurTarget() { }
}
```