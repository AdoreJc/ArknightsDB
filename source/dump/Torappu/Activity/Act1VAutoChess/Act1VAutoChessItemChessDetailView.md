# Act1VAutoChessItemChessDetailView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _itemIconImg`

- `Image _itemLevelIconImg`

- `Text _itemNameText`

- `SingleDescPanel _singleDescPanel`

- `FullDescPanel _fullDescPanel`

- `MoveAnimGroup _rightMoveAnimGroup`

- `MoveAnimGroup _leftMoveAnimGroup`

- `Boolean m_isInited`

- `UICompDialogFinder m_dialogFinder`

- `Int32 m_cachedMoveSeqNum`

- `Act1VAutoChessItemChessDetailItemViewModel m_cachedItemViewModelForKill`

- `Tween m_cachedMoveTween`


## Methods

- `Void Render(Act1VAutoChessItemChessDetailViewModel)`

- `Void _InitIfNot()`

- `Void _RenderItem(Act1VAutoChessItemChessDetailItemViewModel)`

- `Void _OnMoveHideTweenComplete()`

- `Void _ResetScrollRect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessItemChessDetailView : MonoBehaviour, IHotfixable
{
	private Image _itemIconImg; // 0x18
	private Image _itemLevelIconImg; // 0x20
	private Text _itemNameText; // 0x28
	private SingleDescPanel _singleDescPanel; // 0x30
	private FullDescPanel _fullDescPanel; // 0x38
	private MoveAnimGroup _rightMoveAnimGroup; // 0x40
	private MoveAnimGroup _leftMoveAnimGroup; // 0x48
	private ScrollRect[] _descScrollRects; // 0x50
	private Boolean m_isInited; // 0x58
	private UICompDialogFinder m_dialogFinder; // 0x60
	private Int32 m_cachedMoveSeqNum; // 0x70
	private Act1VAutoChessItemChessDetailItemViewModel m_cachedItemViewModelForKill; // 0x78
	private Tween m_cachedMoveTween; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderItem; // 0x10
	private static DelegateBridge __Hotfix0__OnMoveHideTweenComplete; // 0x18
	private static DelegateBridge __Hotfix0__ResetScrollRect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x335b390 VA: 0x7595973390
	public Void Render(Act1VAutoChessItemChessDetailViewModel viewModel) { }
	// RVA: 0x335b558 VA: 0x7595973558
	private Void _InitIfNot() { }
	// RVA: 0x335b5f0 VA: 0x75959735f0
	private Void _RenderItem(Act1VAutoChessItemChessDetailItemViewModel itemViewModel) { }
	// RVA: 0x335becc VA: 0x7595973ecc
	private Void _OnMoveHideTweenComplete() { }
	// RVA: 0x335bf40 VA: 0x7595973f40
	private Void _ResetScrollRect() { }
	// RVA: 0x335c024 VA: 0x7595974024
	public Void .ctor() { }
}
```