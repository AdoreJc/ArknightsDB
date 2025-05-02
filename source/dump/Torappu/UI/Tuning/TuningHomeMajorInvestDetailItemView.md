# TuningHomeMajorInvestDetailItemView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _panelNext`

- `Image _imgCharAvatar`

- `RectTransform _itemCardContainer`

- `CanvasGroup _canvasGroupItemCard`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(TuningHomeMajorInvestItemViewModel, Boolean)`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestDetailItemView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_ITEM_CARD_COMPLETE; // 0x0
	private const Single ALPHA_ITEM_CARD_NORMAL; // 0x0
	private const Single ITEM_CARD_SCALE; // 0x0
	private static readonly Color COLOR_AVATAR_COMPLETE; // 0x0
	private static readonly Color COLOR_AVATAR_UNCOMPLETE; // 0x10
	private GameObject[] _panelComplete; // 0x18
	private GameObject[] _panelUncomplete; // 0x20
	private GameObject _panelNext; // 0x28
	private Image _imgCharAvatar; // 0x30
	private RectTransform _itemCardContainer; // 0x38
	private CanvasGroup _canvasGroupItemCard; // 0x40
	private Boolean m_hasInited; // 0x48
	private UIItemCard m_itemCard; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x232c074 VA: 0x7594944074
	public Void Render(TuningHomeMajorInvestItemViewModel model, Boolean isLast) { }
	// RVA: 0x232c3a0 VA: 0x75949443a0
	private Void _InitIfNot() { }
	// RVA: 0x232c5c0 VA: 0x75949445c0
	private Void _OnItemCardClick(Int32 index) { }
	// RVA: 0x232c6d8 VA: 0x75949446d8
	public Void .ctor() { }
	// RVA: 0x232c758 VA: 0x7594944758
	private static Void .cctor() { }
}
```