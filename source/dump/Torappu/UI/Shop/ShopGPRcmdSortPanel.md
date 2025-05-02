# ShopGPRcmdSortPanel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopGPCommonItemView _itemView`

- `ShopGPMonthlySubItem _monthlyItemView`

- `ScrollRect _scrollRect`

- `UIRecycleHorizonLayoutGroup _content`

- `CanvasGroup _rootCg`

- `Boolean m_isInited`

- `FadeSwitchTween m_switchTween`

- `Holder m_holder`

- `ShopGPSimplePanelAdapter m_adapter`

- `ShopGPRecommedPanelModel m_cachedViewModel`


## Methods

- `Void _InitIfNot()`

- `Void _ResetScrollPos()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPRcmdSortPanel : ShopGPDisplayPanelBase`1
{
	private ShopGPCommonItemView _itemView; // 0x20
	private ShopGPMonthlySubItem _monthlyItemView; // 0x28
	private ScrollRect _scrollRect; // 0x30
	private UIRecycleHorizonLayoutGroup _content; // 0x38
	private CanvasGroup _rootCg; // 0x40
	private Boolean m_isInited; // 0x48
	private FadeSwitchTween m_switchTween; // 0x50
	private Holder m_holder; // 0x58
	private ShopGPSimplePanelAdapter m_adapter; // 0x60
	private ShopGPRecommedPanelModel m_cachedViewModel; // 0x68
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0_SetShow; // 0x18
	private static DelegateBridge __Hotfix0__ResetScrollPos; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override ShopGPPanelType type { get; }

	// RVA: 0x2440610 VA: 0x7594a58610
	protected override ShopGPPanelType get_type() { }
	// RVA: 0x2440678 VA: 0x7594a58678
	private Void _InitIfNot() { }
	// RVA: 0x2440880 VA: 0x7594a58880
	protected override Void OnRender(ShopGPRecommedPanelModel panelModel) { }
	// RVA: 0x2440930 VA: 0x7594a58930
	protected override Void SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2440a00 VA: 0x7594a58a00
	private Void _ResetScrollPos() { }
	// RVA: 0x2440a90 VA: 0x7594a58a90
	public Void .ctor() { }
}
```