# SandboxV2AdminShopItemDetailState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminShopItemDetailView _itemView`

- `SandboxV2AdminShopItemDetailTopBarView _topBarView`

- `SandboxV2AdminShopItemDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnBackClicked()`

- `Void _InitIfNot()`

- `Void _OnIncreaseBtnClicked()`

- `Void _OnDecreaseBtnClicked()`

- `Void _OnBuyItem()`

- `Void _OnBuyRequestProceed(SandboxV2ShopBuyResponse)`

- `Void _OnGainItemDialogClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminShopItemDetailState : PopupFloatState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_INCREASE_BUY_COUNT; // 0x0
	public const Int32 ON_DECREASE_BUY_COUNT; // 0x0
	public const Int32 ON_BUY_ITEM; // 0x0
	private SandboxV2AdminShopItemDetailView _itemView; // 0x70
	private SandboxV2AdminShopItemDetailTopBarView _topBarView; // 0x78
	private SandboxV2AdminShopItemDetailStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnIncreaseBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnDecreaseBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnBuyItem; // 0x38
	private static DelegateBridge __Hotfix0__OnBuyRequestProceed; // 0x40
	private static DelegateBridge __Hotfix0__OnGainItemDialogClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x24f774c VA: 0x7594b0f74c
	protected override Void OnEnter() { }
	// RVA: 0x24f7ee8 VA: 0x7594b0fee8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x24f7f50 VA: 0x7594b0ff50
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x24f8410 VA: 0x7594b10410
	public Void EventOnBackClicked() { }
	// RVA: 0x24f7840 VA: 0x7594b0f840
	private Void _InitIfNot() { }
	// RVA: 0x24f8034 VA: 0x7594b10034
	private Void _OnIncreaseBtnClicked() { }
	// RVA: 0x24f80fc VA: 0x7594b100fc
	private Void _OnDecreaseBtnClicked() { }
	// RVA: 0x24f81c4 VA: 0x7594b101c4
	private Void _OnBuyItem() { }
	// RVA: 0x24f8650 VA: 0x7594b10650
	private Void _OnBuyRequestProceed(SandboxV2ShopBuyResponse response) { }
	// RVA: 0x24f88bc VA: 0x7594b108bc
	private Void _OnGainItemDialogClicked() { }
	// RVA: 0x24f89e4 VA: 0x7594b109e4
	public Void .ctor() { }
	// RVA: 0x24f8b3c VA: 0x7594b10b3c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```