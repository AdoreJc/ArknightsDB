# GrocerySellResultState

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GrocerySellResultView _sellResultView`

- `GrocerySellIncomingLogView _incomingLogPanelViewPrefab`

- `Transform _incomingLogParent`

- `AnimationWrapper _stateEnterAnim`

- `GrocerySellResultStateBean m_stateBean`

- `Boolean m_hasInited`

- `String m_actId`

- `SellGoodState m_sellGoodState`

- `Tween m_stateEnterTween`

- `Tween m_incomingLogEnterTween`

- `GrocerySellIncomingLogView m_incomingLogPanelView`

- `AnimationWrapper m_incomingLogEnterAnim`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _OnNextClick()`

- `Void _OnCloseIncomingPanelClick()`

- `Void _HandleSettleResponse(GrocerySaleSettleResponse)`

- `IEnumerator _TryDismissSelf()`

- `IEnumerator _PlayDiagramTween()`

- `IEnumerator _PlayIncomeTextTween()`

- `IEnumerator _PlayIncomingLogPanelTextTweenWithDelay()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultState : State, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_MSG_NEXT_BUTTON_CLICKED; // 0x0
	public const Int32 ON_MSG_CLOCK_LOG_PANEL_BUTTON_CLICKED; // 0x0
	private const String STATE_ENTER_ANIM_NAME; // 0x0
	private const String INCOMING_LOG_ENTER_ANIM_NAME; // 0x0
	private const Single DIAGRAM_TWEEN_DURATION; // 0x0
	private const Single DIAGRAM_TWEEN_DELAY; // 0x0
	private const Single DIAGRAM_TWEEN_APPEAR_DELAY; // 0x0
	private const Single INCOME_TWEEN_DURATION; // 0x0
	private const Single INCOME_TWEEN_DELAY; // 0x0
	private GrocerySellResultView _sellResultView; // 0x50
	private GrocerySellIncomingLogView _incomingLogPanelViewPrefab; // 0x58
	private Transform _incomingLogParent; // 0x60
	private AnimationWrapper _stateEnterAnim; // 0x68
	private GrocerySellResultStateBean m_stateBean; // 0x70
	private Boolean m_hasInited; // 0x78
	private String m_actId; // 0x80
	private SellGoodState m_sellGoodState; // 0x88
	private Tween m_stateEnterTween; // 0x90
	private Tween m_incomingLogEnterTween; // 0x98
	private GrocerySellIncomingLogView m_incomingLogPanelView; // 0xa0
	private AnimationWrapper m_incomingLogEnterAnim; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnNextClick; // 0x20
	private static DelegateBridge __Hotfix0__OnCloseIncomingPanelClick; // 0x28
	private static DelegateBridge __Hotfix0__HandleSettleResponse; // 0x30
	private static DelegateBridge __Hotfix0__TryDismissSelf; // 0x38
	private static DelegateBridge __Hotfix0__PlayDiagramTween; // 0x40
	private static DelegateBridge __Hotfix0__PlayIncomeTextTween; // 0x48
	private static DelegateBridge __Hotfix0__PlayIncomingLogPanelTextTweenWithDelay; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x28a3bc0 VA: 0x7594ebbbc0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28a3c28 VA: 0x7594ebbc28
	protected override Void OnEnter() { }
	// RVA: 0x28a42b4 VA: 0x7594ebc2b4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28a3e84 VA: 0x7594ebbe84
	private Void _InitIfNot() { }
	// RVA: 0x28a4378 VA: 0x7594ebc378
	private Void _OnNextClick() { }
	// RVA: 0x28a46e4 VA: 0x7594ebc6e4
	private Void _OnCloseIncomingPanelClick() { }
	// RVA: 0x28a49e0 VA: 0x7594ebc9e0
	private Void _HandleSettleResponse(GrocerySaleSettleResponse response) { }
	// RVA: 0x28a4cd0 VA: 0x7594ebccd0
	private IEnumerator _TryDismissSelf() { }
	// RVA: 0x28a415c VA: 0x7594ebc15c
	private IEnumerator _PlayDiagramTween() { }
	// RVA: 0x28a4208 VA: 0x7594ebc208
	private IEnumerator _PlayIncomeTextTween() { }
	// RVA: 0x28a4c24 VA: 0x7594ebcc24
	private IEnumerator _PlayIncomingLogPanelTextTweenWithDelay() { }
	// RVA: 0x28a4e1c VA: 0x7594ebce1c
	public Void .ctor() { }
	// RVA: 0x28a4ec8 VA: 0x7594ebcec8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```