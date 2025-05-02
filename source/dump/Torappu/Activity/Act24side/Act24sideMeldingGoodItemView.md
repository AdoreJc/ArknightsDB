# Act24sideMeldingGoodItemView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Transform _itemContainer`

- `Single _itemScale`

- `Text _txtRemainCount`

- `CanvasGroup _canvasAllConsumedMask`

- `UIAtlasImage _imgHasCountBg`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemModel`

- `FadeSwitchTween m_tweenAllComsumedMask`


## Methods

- `Void Render(Act24sideMeldingGoodItemViewModel)`

- `Void _InitIfNot()`

- `Color _GetRemainBgCol(Boolean, String)`

- `Void _OnClickItemButton(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMeldingGoodItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Single _itemScale; // 0x20
	private Text _txtRemainCount; // 0x28
	private CanvasGroup _canvasAllConsumedMask; // 0x30
	private UIAtlasImage _imgHasCountBg; // 0x38
	private Boolean m_hasInited; // 0x40
	private UIItemCard m_itemCard; // 0x48
	private UIItemViewModel m_itemModel; // 0x50
	private FadeSwitchTween m_tweenAllComsumedMask; // 0x58
	private static readonly String COL_COUNT_ALL_CONSUMED_BG; // 0x0
	private static readonly String UNLIMIT_TAG; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__GetRemainBgCol; // 0x20
	private static DelegateBridge __Hotfix0__OnClickItemButton; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32a1e30 VA: 0x75958b9e30
	public Void Render(Act24sideMeldingGoodItemViewModel model) { }
	// RVA: 0x32a33b4 VA: 0x75958bb3b4
	private Void _InitIfNot() { }
	// RVA: 0x32a34a8 VA: 0x75958bb4a8
	private Color _GetRemainBgCol(Boolean isAllConsumed, String remainBgCol) { }
	// RVA: 0x32a35ac VA: 0x75958bb5ac
	private Void _OnClickItemButton(Int32 index) { }
	// RVA: 0x32a365c VA: 0x75958bb65c
	public Void .ctor() { }
	// RVA: 0x32a36e8 VA: 0x75958bb6e8
	private static Void .cctor() { }
}
```