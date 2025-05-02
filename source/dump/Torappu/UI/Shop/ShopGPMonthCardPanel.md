# ShopGPMonthCardPanel

**Namespace:** `Torappu.UI.Shop`


## Fields

- `Text _remainTime`

- `Text _price`

- `CanvasGroup _rootCg`

- `Boolean m_isInited`

- `FadeSwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`

- `ShopGPMonthlySubItemViewModel m_cacheViewModel`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopGPMonthCardPanel : ShopGPDisplayPanelBase`1
{
	private Text _remainTime; // 0x20
	private Text _price; // 0x28
	private CanvasGroup _rootCg; // 0x30
	private Boolean m_isInited; // 0x38
	private FadeSwitchTween m_switchTween; // 0x40
	private UIStateFinder m_stateFinder; // 0x48
	private ShopGPMonthlySubItemViewModel m_cacheViewModel; // 0x58
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_SetShow; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override ShopGPPanelType type { get; }

	// RVA: 0x243ffc4 VA: 0x7594a57fc4
	protected override ShopGPPanelType get_type() { }
	// RVA: 0x244002c VA: 0x7594a5802c
	protected override Void OnRender(ShopGPMonthCardPanelModel panelModel) { }
	// RVA: 0x24401dc VA: 0x7594a581dc
	protected override Void SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x244010c VA: 0x7594a5810c
	private Void _InitIfNot() { }
	// RVA: 0x244028c VA: 0x7594a5828c
	public Void OnClick() { }
	// RVA: 0x2440580 VA: 0x7594a58580
	public Void .ctor() { }
}
```