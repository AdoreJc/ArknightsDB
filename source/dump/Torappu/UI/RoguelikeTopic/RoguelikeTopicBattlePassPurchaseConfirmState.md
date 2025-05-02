# RoguelikeTopicBattlePassPurchaseConfirmState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassPurchaseConfirmView _confirmView`

- `StateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _ReceiveItems(List`1, Action)`

- `Void _DoPurchase()`

- `Void OnBtnPurchaseClicked()`

- `Void <_DoPurchase>b__8_0(RoguelikeTopicBattlePassPurchaseResponse)`

- `Void <_DoPurchase>b__8_1()`

- `Void <OnBtnPurchaseClicked>b__9_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseConfirmState : PopupFloatState
{
	private RoguelikeTopicBattlePassPurchaseConfirmView _confirmView; // 0x70
	private StateBean m_stateBean; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ReceiveItems; // 0x18
	private static DelegateBridge __Hotfix0__DoPurchase; // 0x20
	private static DelegateBridge __Hotfix0_OnBtnPurchaseClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2637540 VA: 0x7594c4f540
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26375a8 VA: 0x7594c4f5a8
	protected override Void OnEnter() { }
	// RVA: 0x263764c VA: 0x7594c4f64c
	private Void _InitIfNot() { }
	// RVA: 0x26378a4 VA: 0x7594c4f8a4
	private IEnumerator _ReceiveItems(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x26379a4 VA: 0x7594c4f9a4
	private Void _DoPurchase() { }
	// RVA: 0x2637cd4 VA: 0x7594c4fcd4
	public Void OnBtnPurchaseClicked() { }
	// RVA: 0x2638088 VA: 0x7594c50088
	public Void .ctor() { }
	// RVA: 0x26381e4 VA: 0x7594c501e4
	private Void <_DoPurchase>b__8_0(RoguelikeTopicBattlePassPurchaseResponse response) { }
	// RVA: 0x26382a0 VA: 0x7594c502a0
	private Void <_DoPurchase>b__8_1() { }
	// RVA: 0x2638370 VA: 0x7594c50370
	private Void <OnBtnPurchaseClicked>b__9_0() { }
	// RVA: 0x2638374 VA: 0x7594c50374
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```