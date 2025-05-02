# Act1VAutoChessEntryRewardRuleView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEntryRewardRuleListAdapter _listAdapter`

- `Text _basicRewardDescText`

- `Text _extraRewardDescText`

- `Text _extraRewardNum0Text`

- `Text _extraRewardNum1Text`

- `LoopHorizontalScrollRect _loopHorizontalScrollRect`

- `GridLayoutGroup _gridLayout`

- `Graphic _listRaycastTarget`

- `Single _jumpTime`

- `HideArrowIfScrollAtLastItem _hideArrow`

- `AutoHideComponent _scrollBarAutoHide`

- `Boolean m_isInited`

- `Int32 m_cachedEnterSeqNum`

- `Int32 m_cachedJumpSeqNum`

- `Tween m_jumpTween`


## Methods

- `Void Render(Act1VAutoChessEntryRewardRuleViewModel)`

- `Void _InitIfNot()`

- `Void _OnListMove(Vector2)`

- `Void _StartJumpToEnd()`

- `Void _OnJumpComplete()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryRewardRuleView : MonoBehaviour, IHotfixable
{
	private Act1VAutoChessEntryRewardRuleListAdapter _listAdapter; // 0x18
	private Text[] _listTitleTexts; // 0x20
	private Text _basicRewardDescText; // 0x28
	private Text _extraRewardDescText; // 0x30
	private Text _extraRewardNum0Text; // 0x38
	private Text _extraRewardNum1Text; // 0x40
	private LoopHorizontalScrollRect _loopHorizontalScrollRect; // 0x48
	private GridLayoutGroup _gridLayout; // 0x50
	private Graphic _listRaycastTarget; // 0x58
	private Single _jumpTime; // 0x60
	private HideArrowIfScrollAtLastItem _hideArrow; // 0x68
	private AutoHideComponent _scrollBarAutoHide; // 0x70
	private Boolean m_isInited; // 0x78
	private Int32 m_cachedEnterSeqNum; // 0x7c
	private Int32 m_cachedJumpSeqNum; // 0x80
	private Tween m_jumpTween; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnListMove; // 0x10
	private static DelegateBridge __Hotfix0__StartJumpToEnd; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpComplete; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x334179c VA: 0x759595979c
	public Void Render(Act1VAutoChessEntryRewardRuleViewModel viewModel) { }
	// RVA: 0x334299c VA: 0x759595a99c
	private Void _InitIfNot() { }
	// RVA: 0x3343040 VA: 0x759595b040
	private Void _OnListMove(Vector2 input) { }
	// RVA: 0x3342b0c VA: 0x759595ab0c
	private Void _StartJumpToEnd() { }
	// RVA: 0x33430d8 VA: 0x759595b0d8
	private Void _OnJumpComplete() { }
	// RVA: 0x33431a0 VA: 0x759595b1a0
	public Void .ctor() { }
}
```