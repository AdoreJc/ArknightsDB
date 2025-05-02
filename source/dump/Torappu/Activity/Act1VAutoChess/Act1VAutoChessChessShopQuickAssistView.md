# Act1VAutoChessChessShopQuickAssistView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _txtAssistInfo`

- `Act1VAutoChessChessShopQuickAssistTitleWithItemView _titleWithItemViewPrefab`

- `Act1VAutoChessChessShopQuickAssistOnlyItemView _onlyItemViewPrefab`

- `UIRecycleHorizonLayoutGroup _recycleLayoutList`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `Text _txtTipsInfo`

- `UILayoutDimensionListener _dimensionListener`

- `Boolean m_hasInited`

- `Act1VAutoChessChessShopAssistListRecycleAdapter m_adapter`

- `Coroutine m_scrollToGroupCoroutine`

- `Int32 m_cachedEnterSequenceNum`

- `Tween m_focusTween`

- `Act1VAutoChessEntryPage m_page`

- `Boolean m_rendered`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void Init(Act1VAutoChessEntryPage)`

- `Void _InitIfNot()`

- `Void _TryStartScrollCo(Single, Boolean)`

- `IEnumerator _WaitForLayoutReady()`

- `IEnumerator _TryScrollToPos(Single, Boolean)`

- `Void _FocusToPos(Single, Boolean)`

- `Void _TryStartTutorial()`

- `IEnumerator _TutorialOnly_TryRaiseAVGSignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopQuickAssistView : DataBinder`1
{
	private Text _txtAssistInfo; // 0x20
	private Act1VAutoChessChessShopQuickAssistTitleWithItemView _titleWithItemViewPrefab; // 0x28
	private Act1VAutoChessChessShopQuickAssistOnlyItemView _onlyItemViewPrefab; // 0x30
	private UIRecycleHorizonLayoutGroup _recycleLayoutList; // 0x38
	private RectTransform _viewport; // 0x40
	private ScrollRect _scrollView; // 0x48
	private Text _txtTipsInfo; // 0x50
	private UILayoutDimensionListener _dimensionListener; // 0x58
	private const String ASSIST_INFO_FORMAT; // 0x0
	private Boolean m_hasInited; // 0x60
	private Act1VAutoChessChessShopAssistListRecycleAdapter m_adapter; // 0x68
	private Coroutine m_scrollToGroupCoroutine; // 0x70
	private Int32 m_cachedEnterSequenceNum; // 0x78
	private Tween m_focusTween; // 0x80
	private const Single FOCUS_TWEEN_DURATION; // 0x0
	private Act1VAutoChessEntryPage m_page; // 0x88
	private Boolean m_rendered; // 0x90
	private Coroutine m_tutorialCoroutine; // 0x98
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__TryStartScrollCo; // 0x18
	private static DelegateBridge __Hotfix0__WaitForLayoutReady; // 0x20
	private static DelegateBridge __Hotfix0__TryScrollToPos; // 0x28
	private static DelegateBridge __Hotfix0__FocusToPos; // 0x30
	private static DelegateBridge __Hotfix0__TryStartTutorial; // 0x38
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRaiseAVGSignal; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x331ffbc VA: 0x7595937fbc
	public Void Init(Act1VAutoChessEntryPage page) { }
	// RVA: 0x3320040 VA: 0x7595938040
	public override Void OnValueChanged(Act1VAutoChessChessShopQuickAssistViewProperty property) { }
	// RVA: 0x3320214 VA: 0x7595938214
	private Void _InitIfNot() { }
	// RVA: 0x3320d18 VA: 0x7595938d18
	private Void _TryStartScrollCo(Single pos, Boolean isFastMode) { }
	// RVA: 0x3321128 VA: 0x7595939128
	private IEnumerator _WaitForLayoutReady() { }
	// RVA: 0x3321048 VA: 0x7595939048
	private IEnumerator _TryScrollToPos(Single pos, Boolean isFastMode) { }
	// RVA: 0x3321224 VA: 0x7595939224
	private Void _FocusToPos(Single pos, Boolean fastMode) { }
	// RVA: 0x3320e08 VA: 0x7595938e08
	private Void _TryStartTutorial() { }
	// RVA: 0x3321460 VA: 0x7595939460
	private IEnumerator _TutorialOnly_TryRaiseAVGSignal() { }
	// RVA: 0x3321534 VA: 0x7595939534
	public Void .ctor() { }
}
```