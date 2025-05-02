# UIBattleLegionShowCardLibraryPanel

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `RectTransform _cardListScrollView`

- `RectTransform _usedCardIcon`

- `RectTransform _pendingCardIcon`

- `UIAtlasImage _mask`

- `SimpleLayoutContent _cardList`

- `ContentSizeFitter _contentFitter`

- `RectTransform _grid`

- `CardListAdapter m_cardListAdapter`

- `LegionUICardShowCardLibraryState m_legionState`

- `BattleLegionCardLibraryParam m_libraryData`

- `Boolean m_hasInited`

- `CanvasGroup m_svCanScroll`


## Methods

- `Void _InitIfNot()`

- `Void Init(LegionUICardShowCardLibraryState, BattleLegionCardLibraryParam)`

- `Void _ShowCardLibrary()`

- `Void _SortPending(List`1)`

- `Void _SortUsed(List`1)`

- `Void CloseLibraryPanel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class UIBattleLegionShowCardLibraryPanel : MonoBehaviour, IHotfixable
{
	private const Int32 DOUBLE_LINE_LIST_COUNT; // 0x0
	private RectTransform _cardListScrollView; // 0x18
	private RectTransform _usedCardIcon; // 0x20
	private RectTransform _pendingCardIcon; // 0x28
	private UIAtlasImage _mask; // 0x30
	private SimpleLayoutContent _cardList; // 0x38
	private ContentSizeFitter _contentFitter; // 0x40
	private RectTransform _grid; // 0x48
	private CardListAdapter m_cardListAdapter; // 0x50
	private List`1 m_cardList; // 0x58
	private LegionUICardShowCardLibraryState m_legionState; // 0x60
	private BattleLegionCardLibraryParam m_libraryData; // 0x68
	private Boolean m_hasInited; // 0x78
	private CanvasGroup m_svCanScroll; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__ShowCardLibrary; // 0x10
	private static DelegateBridge __Hotfix0__SortPending; // 0x18
	private static DelegateBridge __Hotfix0__SortUsed; // 0x20
	private static DelegateBridge __Hotfix0_CloseLibraryPanel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1db83e0 VA: 0x75943d03e0
	private Void _InitIfNot() { }
	// RVA: 0x1db8660 VA: 0x75943d0660
	public Void Init(LegionUICardShowCardLibraryState legionState, BattleLegionCardLibraryParam libraryData) { }
	// RVA: 0x1db8788 VA: 0x75943d0788
	private Void _ShowCardLibrary() { }
	// RVA: 0x1db8918 VA: 0x75943d0918
	private Void _SortPending(List`1 source) { }
	// RVA: 0x1db8a68 VA: 0x75943d0a68
	private Void _SortUsed(List`1 source) { }
	// RVA: 0x1db8b0c VA: 0x75943d0b0c
	public Void CloseLibraryPanel() { }
	// RVA: 0x1db8b80 VA: 0x75943d0b80
	public Void .ctor() { }
}
```