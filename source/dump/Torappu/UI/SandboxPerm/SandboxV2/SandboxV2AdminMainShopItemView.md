# SandboxV2AdminMainShopItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgIcon`

- `GameObject _panelCount`

- `Text _textCount`

- `Text _textName`

- `CanvasGroup _canvasItemIcon`

- `Text _textStock`

- `GameObject _panelGold`

- `GameObject _panelDimensionCoin`

- `Text _textCurrentPrice`

- `Text _textOriginPrice`

- `GameObject _panelDiscount`

- `Image _imgGold`

- `Image _imgDimensionCoin`

- `Int32 m_cachedIndex`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void set_onItemClicked(Action`1)`

- `Void Render(SandboxV2AdminMainShopItemViewModel)`

- `Void OnItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainShopItemView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_SOLD_OUT; // 0x0
	private const Single ALPHA_NORMAL; // 0x0
	private GameObject[] _panelSoldout; // 0x18
	private GameObject[] _panelNormal; // 0x20
	private Image _imgIcon; // 0x28
	private GameObject _panelCount; // 0x30
	private Text _textCount; // 0x38
	private Text _textName; // 0x40
	private CanvasGroup _canvasItemIcon; // 0x48
	private Text _textStock; // 0x50
	private GameObject _panelGold; // 0x58
	private GameObject _panelDimensionCoin; // 0x60
	private Text _textCurrentPrice; // 0x68
	private Text _textOriginPrice; // 0x70
	private GameObject _panelDiscount; // 0x78
	private Image _imgGold; // 0x80
	private Image _imgDimensionCoin; // 0x88
	private Int32 m_cachedIndex; // 0x90
	private UIPage <page>k__BackingField; // 0x98
	private Action`1 <onItemClicked>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnItemClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UIPage page { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x24e9478 VA: 0x7594b01478
	private UIPage get_page() { }
	// RVA: 0x24e8a74 VA: 0x7594b00a74
	public Void set_page(UIPage value) { }
	// RVA: 0x24e94e0 VA: 0x7594b014e0
	private Action`1 get_onItemClicked() { }
	// RVA: 0x24e8af8 VA: 0x7594b00af8
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x24e8b7c VA: 0x7594b00b7c
	public Void Render(SandboxV2AdminMainShopItemViewModel model) { }
	// RVA: 0x24e9548 VA: 0x7594b01548
	public Void OnItemClicked() { }
	// RVA: 0x24e95e8 VA: 0x7594b015e8
	public Void .ctor() { }
}
```