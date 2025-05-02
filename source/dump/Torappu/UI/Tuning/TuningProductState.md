# TuningProductState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductMenuView _menuView`

- `TuningProductView _productView`

- `UIAnimationLocation _entryAnimLocation`

- `RectTransform _topMenuContainer`

- `TuningProductStateBean m_stateBean`

- `Tween m_entryTween`

- `String m_actId`

- `Boolean m_isInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _TryConsumeGuidebook()`

- `Void _PlayCurMusic(Boolean)`

- `Void _SelectFrag(String)`

- `Void _SelectOrche(String)`

- `Void _ClearAllFrag()`

- `Void _NextStep()`

- `Void _BackSelectFrag()`

- `Void _TransToPlayState()`

- `Void _TransToBagState()`

- `Void _TransSelectOrche(TuningProductViewModel)`

- `Void _ProductMusic()`

- `Void _OnBackBtnPressed()`

- `Void _OnTransToConfirmState(IStateBean)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductState : PopupFadeState, IValueMsgReceiver
{
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	private TuningProductMenuView _menuView; // 0x70
	private TuningProductView _productView; // 0x78
	private UIAnimationLocation _entryAnimLocation; // 0x80
	private RectTransform _topMenuContainer; // 0x90
	public const Int32 SELECT_FRAG; // 0x0
	public const Int32 CLEAR_ALL_FRAG; // 0x0
	public const Int32 NEXT_STEP; // 0x0
	public const Int32 BACK_SELECT_FRAG; // 0x0
	public const Int32 TRANS_TO_PLAY_STATE; // 0x0
	public const Int32 TRANS_TO_BAG_STATE; // 0x0
	private TuningProductStateBean m_stateBean; // 0x98
	private Tween m_entryTween; // 0xa0
	private String m_actId; // 0xa8
	private Boolean m_isInited; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnMessage; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x40
	private static DelegateBridge __Hotfix0__PlayCurMusic; // 0x48
	private static DelegateBridge __Hotfix0__SelectFrag; // 0x50
	private static DelegateBridge __Hotfix0__SelectOrche; // 0x58
	private static DelegateBridge __Hotfix0__ClearAllFrag; // 0x60
	private static DelegateBridge __Hotfix0__NextStep; // 0x68
	private static DelegateBridge __Hotfix0__BackSelectFrag; // 0x70
	private static DelegateBridge __Hotfix0__TransToPlayState; // 0x78
	private static DelegateBridge __Hotfix0__TransToBagState; // 0x80
	private static DelegateBridge __Hotfix0__TransSelectOrche; // 0x88
	private static DelegateBridge __Hotfix0__ProductMusic; // 0x90
	private static DelegateBridge __Hotfix0__OnBackBtnPressed; // 0x98
	private static DelegateBridge __Hotfix0__OnTransToConfirmState; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2337b98 VA: 0x759494fb98
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2337c00 VA: 0x759494fc00
	protected override Void OnEnter() { }
	// RVA: 0x2337eec VA: 0x759494feec
	protected override Void OnResume() { }
	// RVA: 0x233821c VA: 0x759495021c
	protected override Void OnExit() { }
	// RVA: 0x2338310 VA: 0x7594950310
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x23384a4 VA: 0x75949504a4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x233861c VA: 0x759495061c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2337d48 VA: 0x759494fd48
	private Void _InitIfNot() { }
	// RVA: 0x2338194 VA: 0x7594950194
	private Void _TryConsumeGuidebook() { }
	// RVA: 0x2337fd0 VA: 0x759494ffd0
	private Void _PlayCurMusic(Boolean isMainMusicFromStart) { }
	// RVA: 0x2338758 VA: 0x7594950758
	private Void _SelectFrag(String selectFragId) { }
	// RVA: 0x23392c4 VA: 0x75949512c4
	private Void _SelectOrche(String selectOrcheId) { }
	// RVA: 0x23388dc VA: 0x75949508dc
	private Void _ClearAllFrag() { }
	// RVA: 0x23389fc VA: 0x75949509fc
	private Void _NextStep() { }
	// RVA: 0x2338acc VA: 0x7594950acc
	private Void _BackSelectFrag() { }
	// RVA: 0x2338ba8 VA: 0x7594950ba8
	private Void _TransToPlayState() { }
	// RVA: 0x2338d30 VA: 0x7594950d30
	private Void _TransToBagState() { }
	// RVA: 0x2339690 VA: 0x7594951690
	private Void _TransSelectOrche(TuningProductViewModel model) { }
	// RVA: 0x23397ac VA: 0x75949517ac
	private Void _ProductMusic() { }
	// RVA: 0x2339dc8 VA: 0x7594951dc8
	private Void _OnBackBtnPressed() { }
	// RVA: 0x2339edc VA: 0x7594951edc
	private Void _OnTransToConfirmState(IStateBean stateBean) { }
	// RVA: 0x2339ff0 VA: 0x7594951ff0
	public Void .ctor() { }
	// RVA: 0x233a0a0 VA: 0x75949520a0
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x233a0c8 VA: 0x75949520c8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x233a0d0 VA: 0x75949520d0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x233a0d8 VA: 0x75949520d8
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x233a0e0 VA: 0x75949520e0
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x233a108 VA: 0x7594952108
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```