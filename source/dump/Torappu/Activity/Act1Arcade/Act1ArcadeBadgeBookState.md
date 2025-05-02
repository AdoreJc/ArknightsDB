# Act1ArcadeBadgeBookState

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeBadgeBookView _badgeBookView`

- `CanvasGroup _rootGroup`

- `UIAnimationLocation _inAnimationLocation`

- `Coroutine m_focusCoroutine`

- `Boolean m_isInited`

- `AnimationSwitchTween m_inTween`

- `Int32 m_detailDialogInst`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void _OnOpenDetailEvent(ValueBundle)`

- `Void _OnOpenShareEvent()`

- `Void _OnSwitchLayoutEvent()`

- `Void _InitIfNot()`

- `Void _OnClickBack()`

- `Void _FocusZoneBadgeIfNeed()`

- `IEnumerator _FocusZoneBadgeCoroutine(Int32)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookState : UIPopupState, IValueMsgReceiver, ICompDialogCallBack
{
	private const Single FADE_DURATION; // 0x0
	private Act1ArcadeBadgeBookView _badgeBookView; // 0x60
	private CanvasGroup _rootGroup; // 0x68
	private UIAnimationLocation _inAnimationLocation; // 0x70
	private readonly Act1ArcadeBadgeBookStateBean m_stateBean; // 0x80
	private readonly Act1ArcadeBadgeBookProperty m_property; // 0x88
	private Coroutine m_focusCoroutine; // 0x90
	private Boolean m_isInited; // 0x98
	private AnimationSwitchTween m_inTween; // 0xa0
	private Int32 m_detailDialogInst; // 0xa8
	public const Int32 OPEN_DETAIL_EVENT; // 0x0
	public const Int32 OPEN_SHARE_EVENT; // 0x0
	public const Int32 SWITCH_LAYOUT_EVENT; // 0x0
	private static DelegateBridge __Hotfix0_OnMessage; // 0x0
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x8
	private static DelegateBridge __Hotfix0__OnOpenDetailEvent; // 0x10
	private static DelegateBridge __Hotfix0__OnOpenShareEvent; // 0x18
	private static DelegateBridge __Hotfix0__OnSwitchLayoutEvent; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0__OnClickBack; // 0x40
	private static DelegateBridge __Hotfix0__FocusZoneBadgeIfNeed; // 0x48
	private static DelegateBridge __Hotfix0__FocusZoneBadgeCoroutine; // 0x50
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x68
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x33f7c4c VA: 0x7595a0fc4c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x33f8440 VA: 0x7595a10440
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x33f7d2c VA: 0x7595a0fd2c
	private Void _OnOpenDetailEvent(ValueBundle msg) { }
	// RVA: 0x33f8060 VA: 0x7595a10060
	private Void _OnOpenShareEvent() { }
	// RVA: 0x33f838c VA: 0x7595a1038c
	private Void _OnSwitchLayoutEvent() { }
	// RVA: 0x33f8a3c VA: 0x7595a10a3c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33f8aa4 VA: 0x7595a10aa4
	private Void _InitIfNot() { }
	// RVA: 0x33f8d28 VA: 0x7595a10d28
	protected override Void OnEnter() { }
	// RVA: 0x33f90fc VA: 0x7595a110fc
	private Void _OnClickBack() { }
	// RVA: 0x33f8fcc VA: 0x7595a10fcc
	private Void _FocusZoneBadgeIfNeed() { }
	// RVA: 0x33f9350 VA: 0x7595a11350
	private IEnumerator _FocusZoneBadgeCoroutine(Int32 index) { }
	// RVA: 0x33f943c VA: 0x7595a1143c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x33f95b4 VA: 0x7595a115b4
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x33f972c VA: 0x7595a1172c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x33f9868 VA: 0x7595a11868
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x33f99a4 VA: 0x7595a119a4
	public Void .ctor() { }
	// RVA: 0x33f9b64 VA: 0x7595a11b64
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```