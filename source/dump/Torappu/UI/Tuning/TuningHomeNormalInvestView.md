# TuningHomeNormalInvestView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Image _imgCharAvatar`

- `RectTransform _panelItemCardContainer`

- `CanvasGroup _canvasGroupItemCard`

- `AnimationWrapper _animationWrapper`

- `UIStateFinder m_stateFinder`

- `String m_cacheInvestId`

- `Int32 m_currAnimSeq`

- `Tween m_entryAnim`

- `UIItemCard m_itemCard`

- `Boolean m_hasInited`


## Methods

- `Void Render(TuningHomeNormalInvestViewModel, Int32)`

- `Void EventOnStartInvestClicked()`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`

- `Void _PlayEntryAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeNormalInvestView : MonoBehaviour, IHotfixable
{
	private const Single ITEM_CARD_SCALE; // 0x0
	private const Single ALPHA_COMPLETE; // 0x0
	private const Single ALPHA_UNCOMPLETE; // 0x0
	private static readonly Color COLOR_AVATAR_COMPLETE; // 0x0
	private static readonly Color COLOR_AVATAR_UNCOMPLETE; // 0x10
	private const String ENTRY_ANIM_NAME; // 0x0
	private GameObject[] _panelComplete; // 0x18
	private GameObject[] _panelUncomplete; // 0x20
	private Image _imgCharAvatar; // 0x28
	private Text[] _textName; // 0x30
	private RectTransform _panelItemCardContainer; // 0x38
	private CanvasGroup _canvasGroupItemCard; // 0x40
	private AnimationWrapper _animationWrapper; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private String m_cacheInvestId; // 0x60
	private Int32 m_currAnimSeq; // 0x68
	private Tween m_entryAnim; // 0x70
	private UIItemCard m_itemCard; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnStartInvestClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x38
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x23271b8 VA: 0x759493f1b8
	public Void Render(TuningHomeNormalInvestViewModel viewModel, Int32 entryAnimSeq) { }
	// RVA: 0x23281f8 VA: 0x75949401f8
	public Void EventOnStartInvestClicked() { }
	// RVA: 0x2327ed8 VA: 0x759493fed8
	private Void _InitIfNot() { }
	// RVA: 0x2328340 VA: 0x7594940340
	private Void _OnItemCardClick(Int32 index) { }
	// RVA: 0x23280f8 VA: 0x75949400f8
	private Void _PlayEntryAnim() { }
	// RVA: 0x2328458 VA: 0x7594940458
	public Void .ctor() { }
	// RVA: 0x23284e0 VA: 0x75949404e0
	private static Void .cctor() { }
}
```