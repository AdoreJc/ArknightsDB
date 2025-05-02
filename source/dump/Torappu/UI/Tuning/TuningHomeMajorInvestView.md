# TuningHomeMajorInvestView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `GameObject _panelUnlocked`

- `GameObject _panelUncomplete`

- `GameObject _panelUncompleteOnly`

- `GameObject _panelItemEnough`

- `GameObject _panelItemNotEnough`

- `Image _imgCharacter`

- `RectTransform _panelItemCardContainer`

- `SimpleLayoutContent _progressContent`

- `Text _textProgressCurr`

- `Text _textProgressMax`

- `UIStateFinder m_stateFinder`

- `Adapter m_adapter`

- `UIItemCard m_itemCard`

- `Boolean m_hasInited`

- `Int32 m_cachedCurrIndex`

- `Int32 m_cachedMaxIndex`


## Methods

- `Void Render(TuningHomeMajorInvestViewModel)`

- `Void EventOnUnlockMajorInvestClicked()`

- `Void EventOnStartInvestClicked()`

- `Void EventOnDetailClicked()`

- `Void _InitIfNot()`

- `Void _OnItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestView : MonoBehaviour, IHotfixable
{
	private const Single ITEM_CARD_SCALE; // 0x0
	private GameObject[] _panelLocked; // 0x18
	private GameObject _panelUnlocked; // 0x20
	private GameObject[] _panelComplete; // 0x28
	private GameObject _panelUncomplete; // 0x30
	private GameObject _panelUncompleteOnly; // 0x38
	private GameObject _panelItemEnough; // 0x40
	private GameObject _panelItemNotEnough; // 0x48
	private Text[] _textNpcName; // 0x50
	private Text[] _textItemCountCurr; // 0x58
	private Text[] _textItemCountCost; // 0x60
	private Image _imgCharacter; // 0x68
	private RectTransform _panelItemCardContainer; // 0x70
	private SimpleLayoutContent _progressContent; // 0x78
	private Text _textProgressCurr; // 0x80
	private Text _textProgressMax; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private Adapter m_adapter; // 0xa0
	private UIItemCard m_itemCard; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private Int32 m_cachedCurrIndex; // 0xb4
	private Int32 m_cachedMaxIndex; // 0xb8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnUnlockMajorInvestClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStartInvestClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnDetailClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2326a10 VA: 0x759493ea10
	public Void Render(TuningHomeMajorInvestViewModel viewModel) { }
	// RVA: 0x2327850 VA: 0x759493f850
	public Void EventOnUnlockMajorInvestClicked() { }
	// RVA: 0x23278f4 VA: 0x759493f8f4
	public Void EventOnStartInvestClicked() { }
	// RVA: 0x2327a20 VA: 0x759493fa20
	public Void EventOnDetailClicked() { }
	// RVA: 0x23275f0 VA: 0x759493f5f0
	private Void _InitIfNot() { }
	// RVA: 0x2327b58 VA: 0x759493fb58
	private Void _OnItemCardClick(Int32 index) { }
	// RVA: 0x2327c60 VA: 0x759493fc60
	public Void .ctor() { }
}
```