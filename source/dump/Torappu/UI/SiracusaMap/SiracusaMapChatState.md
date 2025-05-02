# SiracusaMapChatState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaMapPointInfoView _pointInfoPrefab`

- `RectTransform _pointInfoContainer`

- `SiracusaChatController _chatController`

- `SiracusaMapChatStateBean m_stateBean`

- `Boolean m_hasInited`

- `SiracusaMapPointInfoView m_pointInfoView`

- `Bridge m_bridge`


## Methods

- `Void EventOnBackBtnClicked()`

- `Void _InitIfNot()`

- `Void _RedirectTarget()`

- `Void _ClearChatModel()`

- `Void _OnOptionSelect(String)`

- `Void _OnItemObtain(String)`

- `Void _CompleteTaskIfNeed(Action)`

- `Void <_OnOptionSelect>b__19_0(SiracusaMapAvgOptionSelectResponse)`

- `Void <_OnItemObtain>b__20_0(SiracusaMapAvgItemCardGainResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapChatState : PopupFloatState, IHotfixable, ISiracusaReplaceable
{
	private SiracusaMapPointInfoView _pointInfoPrefab; // 0x70
	private RectTransform _pointInfoContainer; // 0x78
	private SiracusaChatController _chatController; // 0x80
	private SiracusaMapChatStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private SiracusaMapPointInfoView m_pointInfoView; // 0x98
	private Bridge m_bridge; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_DealWithOtherStateBeforeTransStart; // 0x20
	private static DelegateBridge __Hotfix0_DealWithOtherStateWenTransEnd; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBackBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__RedirectTarget; // 0x40
	private static DelegateBridge __Hotfix0__ClearChatModel; // 0x48
	private static DelegateBridge __Hotfix0__OnOptionSelect; // 0x50
	private static DelegateBridge __Hotfix0__OnItemObtain; // 0x58
	private static DelegateBridge __Hotfix0__CompleteTaskIfNeed; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x24061bc VA: 0x7594a1e1bc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2406224 VA: 0x7594a1e224
	protected override Void OnEnter() { }
	// RVA: 0x2406888 VA: 0x7594a1e888
	protected override Void OnResume() { }
	// RVA: 0x2406d34 VA: 0x7594a1ed34
	protected override Void OnExit() { }
	// RVA: 0x2406e2c VA: 0x7594a1ee2c
	protected sealed override Void DealWithOtherStateBeforeTransStart(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x2406f84 VA: 0x7594a1ef84
	protected sealed override Void DealWithOtherStateWenTransEnd(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x24070dc VA: 0x7594a1f0dc
	public Void EventOnBackBtnClicked() { }
	// RVA: 0x240638c VA: 0x7594a1e38c
	private Void _InitIfNot() { }
	// RVA: 0x2407744 VA: 0x7594a1f744
	private Void _RedirectTarget() { }
	// RVA: 0x24075b0 VA: 0x7594a1f5b0
	private Void _ClearChatModel() { }
	// RVA: 0x2407900 VA: 0x7594a1f900
	private Void _OnOptionSelect(String optionId) { }
	// RVA: 0x2407c68 VA: 0x7594a1fc68
	private Void _OnItemObtain(String itemId) { }
	// RVA: 0x2407268 VA: 0x7594a1f268
	private Void _CompleteTaskIfNeed(Action onComplete) { }
	// RVA: 0x2407fc0 VA: 0x7594a1ffc0
	public Void .ctor() { }
	// RVA: 0x2408118 VA: 0x7594a20118
	private Void <_OnOptionSelect>b__19_0(SiracusaMapAvgOptionSelectResponse response) { }
	// RVA: 0x240817c VA: 0x7594a2017c
	private Void <_OnItemObtain>b__20_0(SiracusaMapAvgItemCardGainResponse response) { }
	// RVA: 0x24081e0 VA: 0x7594a201e0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x24081e8 VA: 0x7594a201e8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x24081f0 VA: 0x7594a201f0
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x24081f8 VA: 0x7594a201f8
	private Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext P0, Boolean P1) { }
	// RVA: 0x2408224 VA: 0x7594a20224
	private Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext P0, Boolean P1) { }
}
```