# RL04AlchemySlotItemView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `CanvasGroup _canvasFragmentItem`

- `UIColorGraphic _graphicColor`

- `Transform _fragmentCardContainer`

- `RL04AlchemySlotFragmentItemCard _fragmentCardPrefab`

- `Text _txtFragmentName`

- `Text _txtFragmentDesc`

- `Boolean m_hasInited`

- `RL04AlchemySlotFragmentItemCard m_fragmentCard`

- `RL04AlchemySlotItemViewModel m_cachedItemViewModel`

- `FadeSwitchTween m_tweenFragmentItem`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(RL04AlchemySlotItemViewModel)`

- `Void _InitIfNot()`

- `Void _EnsureFragmentCard()`

- `Void EventOnSlotClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemySlotItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasFragmentItem; // 0x18
	private UIColorGraphic _graphicColor; // 0x20
	private Transform _fragmentCardContainer; // 0x28
	private RL04AlchemySlotFragmentItemCard _fragmentCardPrefab; // 0x30
	private Text _txtFragmentName; // 0x38
	private Text _txtFragmentDesc; // 0x40
	private Boolean m_hasInited; // 0x48
	private RL04AlchemySlotFragmentItemCard m_fragmentCard; // 0x50
	private RL04AlchemySlotItemViewModel m_cachedItemViewModel; // 0x58
	private FadeSwitchTween m_tweenFragmentItem; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EnsureFragmentCard; // 0x10
	private static DelegateBridge __Hotfix0_EventOnSlotClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2b0ceec VA: 0x7595124eec
	public Void Render(RL04AlchemySlotItemViewModel slotItemViewModel) { }
	// RVA: 0x2b0d04c VA: 0x759512504c
	private Void _InitIfNot() { }
	// RVA: 0x2b0d130 VA: 0x7595125130
	private Void _EnsureFragmentCard() { }
	// RVA: 0x2b0d260 VA: 0x7595125260
	public Void EventOnSlotClick() { }
	// RVA: 0x2b0d374 VA: 0x7595125374
	public Void .ctor() { }
}
```