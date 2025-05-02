# TuningProductBagPanelView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `CanvasGroup _panelGroup`

- `Single _panelHideAlpha`

- `Single _panelShowAlpha`

- `Single _panelHideDuration`

- `UIAnimationLocation _enterAnimLocation`

- `GameObject _productBtn`

- `GameObject _productBtnWithFrame`

- `GameObject _btnGroup`

- `SimpleLayoutContent _productTypeItemContent`

- `TuningProductBagLoopAdapter _loopAdapter`

- `GameObject _chatStateEmptyObj`

- `GameObject _bagStateEmptyObj`

- `TuningBagCardItemView _hiddenCardView`

- `TuningProductBagViewModel m_cachedBagViewModel`

- `TuningBagSwitchTween m_switchTween`

- `Boolean m_isInited`

- `ProductTypeAdapter m_productTypeItemAdapter`

- `Action onTransToProductState`


## Methods

- `Void Render(TuningProductBagViewModel)`

- `Void _InitIfNot()`

- `Void OnTransToProductState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagPanelView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _panelGroup; // 0x18
	private Single _panelHideAlpha; // 0x20
	private Single _panelShowAlpha; // 0x24
	private Single _panelHideDuration; // 0x28
	private UIAnimationLocation _enterAnimLocation; // 0x30
	private GameObject _productBtn; // 0x40
	private GameObject _productBtnWithFrame; // 0x48
	private GameObject _btnGroup; // 0x50
	private SimpleLayoutContent _productTypeItemContent; // 0x58
	private TuningProductBagLoopAdapter _loopAdapter; // 0x60
	private GameObject _chatStateEmptyObj; // 0x68
	private GameObject _bagStateEmptyObj; // 0x70
	private TuningBagCardItemView _hiddenCardView; // 0x78
	private TuningProductBagViewModel m_cachedBagViewModel; // 0x80
	private TuningBagSwitchTween m_switchTween; // 0x88
	private Boolean m_isInited; // 0x90
	private ProductTypeAdapter m_productTypeItemAdapter; // 0x98
	public Action`1 onSelectCard; // 0xa0
	public Action`1 onSelectProductType; // 0xa8
	public Action onTransToProductState; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnTransToProductState; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23400c8 VA: 0x75949580c8
	public Void Render(TuningProductBagViewModel bagViewModel) { }
	// RVA: 0x2340440 VA: 0x7594958440
	private Void _InitIfNot() { }
	// RVA: 0x2340a60 VA: 0x7594958a60
	public Void OnTransToProductState() { }
	// RVA: 0x2340ae4 VA: 0x7594958ae4
	public Void .ctor() { }
}
```