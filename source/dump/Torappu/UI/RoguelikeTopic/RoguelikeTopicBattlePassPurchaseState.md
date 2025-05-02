# RoguelikeTopicBattlePassPurchaseState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassPurchaseView _battlePassPurchaseView`

- `StateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _OnJumpToOverviewState(IStateBean)`

- `Void _OnJumpToConfirmState(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnWheelBeginScroll()`

- `Void _OnWheelBeginDrag()`

- `Void _OnWheelUpdateIndex(Int32)`

- `Void _OnWheelScrollEnd(Int32)`

- `Void _OnGrandPrizeBtnClicked(String)`

- `Void OnBtnOverviewClicked()`

- `Void OnBtnPurchaseClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseState : PopupFadeState
{
	private RoguelikeTopicBattlePassPurchaseView _battlePassPurchaseView; // 0x70
	private StateBean m_stateBean; // 0x78
	private Boolean m_isInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToOverviewState; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToConfirmState; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnWheelBeginScroll; // 0x30
	private static DelegateBridge __Hotfix0__OnWheelBeginDrag; // 0x38
	private static DelegateBridge __Hotfix0__OnWheelUpdateIndex; // 0x40
	private static DelegateBridge __Hotfix0__OnWheelScrollEnd; // 0x48
	private static DelegateBridge __Hotfix0__OnGrandPrizeBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnOverviewClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnPurchaseClicked; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x263b640 VA: 0x7594c53640
	public override IStateBean GetCacheBean() { }
	// RVA: 0x263b6a8 VA: 0x7594c536a8
	protected override Void OnEnter() { }
	// RVA: 0x263bae8 VA: 0x7594c53ae8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x263bcdc VA: 0x7594c53cdc
	private Void _OnJumpToOverviewState(IStateBean stateBean) { }
	// RVA: 0x263bda4 VA: 0x7594c53da4
	private Void _OnJumpToConfirmState(IStateBean stateBean) { }
	// RVA: 0x263b74c VA: 0x7594c5374c
	private Void _InitIfNot() { }
	// RVA: 0x263bef0 VA: 0x7594c53ef0
	private Void _OnWheelBeginScroll() { }
	// RVA: 0x263bff8 VA: 0x7594c53ff8
	private Void _OnWheelBeginDrag() { }
	// RVA: 0x263c12c VA: 0x7594c5412c
	private Void _OnWheelUpdateIndex(Int32 index) { }
	// RVA: 0x263c2c8 VA: 0x7594c542c8
	private Void _OnWheelScrollEnd(Int32 index) { }
	// RVA: 0x263c458 VA: 0x7594c54458
	private Void _OnGrandPrizeBtnClicked(String grandPrizeId) { }
	// RVA: 0x263c7b0 VA: 0x7594c547b0
	public Void OnBtnOverviewClicked() { }
	// RVA: 0x263c9b8 VA: 0x7594c549b8
	public Void OnBtnPurchaseClicked() { }
	// RVA: 0x263cc08 VA: 0x7594c54c08
	public Void .ctor() { }
	// RVA: 0x263cd64 VA: 0x7594c54d64
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x263cd6c VA: 0x7594c54d6c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```