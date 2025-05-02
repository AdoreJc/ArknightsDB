# VoucherSkinHomeState

**Namespace:** `Torappu.UI.VoucherSkin`


## Fields

- `VoucherSkinHomeView _view`

- `Boolean m_inited`

- `VoucherSkinHomeStateBean m_stateBean`


## Methods

- `Void EventOnBackClicked()`

- `Void EventOnRuleBtnClicked()`

- `Void EventOnRuleDetailMaskClicked()`

- `Void _EventOnGoodClicked(VoucherSkinGoodViewModel)`

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoucherSkin
public class VoucherSkinHomeState : PopupFadeState
{
	private VoucherSkinHomeView _view; // 0x70
	private Boolean m_inited; // 0x78
	private VoucherSkinHomeStateBean m_stateBean; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnRuleBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnRuleDetailMaskClicked; // 0x20
	private static DelegateBridge __Hotfix0__EventOnGoodClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x229127c VA: 0x75948a927c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22912e4 VA: 0x75948a92e4
	protected override Void OnEnter() { }
	// RVA: 0x2291588 VA: 0x75948a9588
	public Void EventOnBackClicked() { }
	// RVA: 0x2291654 VA: 0x75948a9654
	public Void EventOnRuleBtnClicked() { }
	// RVA: 0x229178c VA: 0x75948a978c
	public Void EventOnRuleDetailMaskClicked() { }
	// RVA: 0x2291800 VA: 0x75948a9800
	private Void _EventOnGoodClicked(VoucherSkinGoodViewModel goodModel) { }
	// RVA: 0x2291358 VA: 0x75948a9358
	private Void _InitIfNot() { }
	// RVA: 0x2291aec VA: 0x75948a9aec
	public Void .ctor() { }
	// RVA: 0x2291c08 VA: 0x75948a9c08
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```