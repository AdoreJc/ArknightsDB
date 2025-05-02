# Act1VAutoChessChessShopLevelTrapGroupItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _rectLevelTagViewContainer`

- `Act1VAutoChessChessShopLevelTagView _levelTagViewPrefab`

- `SimpleLayoutContent _trapList`

- `GridLayoutGroup _gridLayout`

- `Boolean m_hasInited`

- `Int32 m_cachedIndex`

- `Act1VAutoChessChessShopLevelTagView m_levelTagView`

- `TrapListAdapter m_adapter`


## Properties

- `GridLayoutGroup gridLayout`


## Methods

- `GridLayoutGroup get_gridLayout()`

- `Void Render(TrapGroupViewParams)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelTrapGroupItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _rectLevelTagViewContainer; // 0x18
	private Act1VAutoChessChessShopLevelTagView _levelTagViewPrefab; // 0x20
	private SimpleLayoutContent _trapList; // 0x28
	private GridLayoutGroup _gridLayout; // 0x30
	private Boolean m_hasInited; // 0x38
	private Int32 m_cachedIndex; // 0x3c
	private Act1VAutoChessChessShopLevelTagView m_levelTagView; // 0x40
	private List`1 m_cachedLevelTrapItemCardViewModelList; // 0x48
	private TrapListAdapter m_adapter; // 0x50
	private static DelegateBridge __Hotfix0_get_gridLayout; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public GridLayoutGroup gridLayout { get; }

	// RVA: 0x3323fd8 VA: 0x759593bfd8
	public GridLayoutGroup get_gridLayout() { }
	// RVA: 0x3324040 VA: 0x759593c040
	public Void Render(TrapGroupViewParams viewParams) { }
	// RVA: 0x3324154 VA: 0x759593c154
	private Void _InitIfNot() { }
	// RVA: 0x33243f8 VA: 0x759593c3f8
	public Void .ctor() { }
}
```