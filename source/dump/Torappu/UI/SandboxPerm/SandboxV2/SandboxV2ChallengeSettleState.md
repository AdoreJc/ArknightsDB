# SandboxV2ChallengeSettleState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ChallengeSettleView _challengeSettleView`

- `UIAnimationLocation _animShow`

- `SandboxV2ChallengeSettleStateBean m_stateBean`

- `Tween m_showTween`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnConfirmClicked()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ChallengeSettleState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_CONFIRM_CLICKED; // 0x0
	private SandboxV2ChallengeSettleView _challengeSettleView; // 0x70
	private UIAnimationLocation _animShow; // 0x78
	private SandboxV2ChallengeSettleStateBean m_stateBean; // 0x88
	private Tween m_showTween; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnConfirmClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x251928c VA: 0x7594b3128c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x25192f4 VA: 0x7594b312f4
	protected override Void OnEnter() { }
	// RVA: 0x25196ec VA: 0x7594b316ec
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2519880 VA: 0x7594b31880
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2519a38 VA: 0x7594b31a38
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2519adc VA: 0x7594b31adc
	private Void _OnConfirmClicked() { }
	// RVA: 0x2519df0 VA: 0x7594b31df0
	public Void .ctor() { }
	// RVA: 0x2519f48 VA: 0x7594b31f48
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2519f70 VA: 0x7594b31f70
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2519f78 VA: 0x7594b31f78
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2519fa0 VA: 0x7594b31fa0
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
}
```