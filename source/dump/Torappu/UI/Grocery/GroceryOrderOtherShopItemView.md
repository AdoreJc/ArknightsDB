# GroceryOrderOtherShopItemView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GameObject _objEmpty`

- `GameObject _objInfo`

- `CanvasGroup _canvasNotInquire`

- `Image _imgIconNotInquire`

- `GameObject _objInquired`

- `Image _imgIconInquired`

- `Text _txtStrategy`

- `GameObject _objExactCount`

- `Text _txtExactCount`

- `GameObject _objRangeCount`

- `Text _txtRangeDownCount`

- `Text _txtRangeUpCount`

- `Boolean m_hasInit`

- `String m_cachedShopId`

- `String m_cachedGoodId`

- `GroceryOrderOtherShopStatus m_cachedStatus`

- `FadeSwitchTween m_notInquireTween`

- `UIStateFinder m_stateFinder`

- `GroceryOrderCountTextTweener m_exactCountTweener`

- `GroceryOrderCountTextTweener m_rangeDownCountTweener`

- `GroceryOrderCountTextTweener m_rangeUpCountTweener`


## Methods

- `Void Render(GroceryOrderOtherShopItemViewModel, String)`

- `Void _InitIfNot()`

- `Void _RefreshOrderCount(GroceryOrderOtherShopItemViewModel, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryOrderOtherShopItemView : MonoBehaviour, IHotfixable
{
	private GameObject _objEmpty; // 0x18
	private GameObject _objInfo; // 0x20
	private CanvasGroup _canvasNotInquire; // 0x28
	private Image _imgIconNotInquire; // 0x30
	private GameObject _objInquired; // 0x38
	private Image _imgIconInquired; // 0x40
	private Text _txtStrategy; // 0x48
	private GameObject _objExactCount; // 0x50
	private Text _txtExactCount; // 0x58
	private GameObject _objRangeCount; // 0x60
	private Text _txtRangeDownCount; // 0x68
	private Text _txtRangeUpCount; // 0x70
	private Boolean m_hasInit; // 0x78
	private String m_cachedShopId; // 0x80
	private String m_cachedGoodId; // 0x88
	private GroceryOrderOtherShopStatus m_cachedStatus; // 0x90
	private FadeSwitchTween m_notInquireTween; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private GroceryOrderCountTextTweener m_exactCountTweener; // 0xb0
	private GroceryOrderCountTextTweener m_rangeDownCountTweener; // 0xb8
	private GroceryOrderCountTextTweener m_rangeUpCountTweener; // 0xc0
	private const Single CNT_CHANGE_DUR; // 0x0
	private const Single INQUIRE_COUNT_NOT_ENOUGH_ALPHA; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RefreshOrderCount; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2887fd8 VA: 0x7594e9ffd8
	public Void Render(GroceryOrderOtherShopItemViewModel itemViewModel, String curChangingGoodId) { }
	// RVA: 0x28891e8 VA: 0x7594ea11e8
	private Void _InitIfNot() { }
	// RVA: 0x28895cc VA: 0x7594ea15cc
	private Void _RefreshOrderCount(GroceryOrderOtherShopItemViewModel itemViewModel, Boolean fastMode) { }
	// RVA: 0x2889a54 VA: 0x7594ea1a54
	public Void OnClick() { }
	// RVA: 0x2889bf8 VA: 0x7594ea1bf8
	public Void .ctor() { }
}
```