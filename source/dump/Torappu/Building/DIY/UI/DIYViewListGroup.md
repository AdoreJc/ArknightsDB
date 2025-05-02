# DIYViewListGroup

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYListView _verticalView`

- `DIYListView _horizontalView`

- `GameObject _pnlListview`

- `GameObject _pnlEmpty`

- `Text _textEmpty`

- `Boolean m_isInit`

- `Single m_cachedPos`

- `UIExpandListState m_cachedExpandedState`

- `DIYListView m_cachedListView`


## Methods

- `Void _InitIfNot()`

- `Void Setup(Boolean)`

- `Void SavePos()`

- `Void Render(DIYViewListModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYViewListGroup : MonoBehaviour, IHotfixable
{
	private DIYListView _verticalView; // 0x18
	private DIYListView _horizontalView; // 0x20
	private GameObject _pnlListview; // 0x28
	private GameObject _pnlEmpty; // 0x30
	private Text _textEmpty; // 0x38
	public Func`2 onButtonPressed; // 0x40
	public Func`2 onInfoPressed; // 0x48
	private Boolean m_isInit; // 0x50
	private Single m_cachedPos; // 0x54
	private UIExpandListState m_cachedExpandedState; // 0x58
	private DIYListView m_cachedListView; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0_SavePos; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x382a32c VA: 0x7595e4232c
	private Void _InitIfNot() { }
	// RVA: 0x3819260 VA: 0x7595e31260
	public Void Setup(Boolean isThemeListView) { }
	// RVA: 0x38196e8 VA: 0x7595e316e8
	public Void SavePos() { }
	// RVA: 0x3819774 VA: 0x7595e31774
	public Void Render(DIYViewListModel viewListModel, Int32 themeStateChangeDirection) { }
	// RVA: 0x382a3bc VA: 0x7595e423bc
	public Void .ctor() { }
}
```