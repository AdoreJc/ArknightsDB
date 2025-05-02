# ItemRepoVoucherGachaState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `GameObject _detailPart`

- `GameObject _rarityCharPart6`

- `GameObject _rarityCharPart5`

- `CanvasGroup _alphaCanvas`

- `Tween m_showTween`


## Methods

- `Void OnUseClick()`

- `Void OnDetailClick()`

- `Void SendGetItem()`

- `Void SendGetChar()`

- `Void _ResetTween()`

- `Void ShowAlpha()`

- `Void ShowChar(CharGachaVoucherData)`

- `Void SendItemVoucherRequest()`

- `Void ShowGachaEffect(GachaResult[], Boolean, Boolean)`

- `Void <SendGetItem>b__10_0(VoucherItemDetailResponse)`

- `Void <SendGetChar>b__11_0(VoucherCharDetailResponse)`

- `Void <SendItemVoucherRequest>b__16_0(useCharGachaVoucherResponse)`

- `Void <RegisterToDataListener>b__17_0(IStateBean)`

- `Void <RegisterToDataListener>b__17_1(IStateBean)`

- `Void <RegisterToDataListener>b__17_2(IStateBean)`

- `IStateBean <>xLuaBaseProxy_GetCacheBean()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherGachaState : ItemRepoItemDetailState
{
	private GameObject _detailPart; // 0xb8
	private GameObject _rarityCharPart6; // 0xc0
	private GameObject _rarityCharPart5; // 0xc8
	private CanvasGroup _alphaCanvas; // 0xd0
	private Tween m_showTween; // 0xd8
	private const Single FADE_DUR; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnUseClick; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x20
	private static DelegateBridge __Hotfix0_SendGetItem; // 0x28
	private static DelegateBridge __Hotfix0_SendGetChar; // 0x30
	private static DelegateBridge __Hotfix0__ResetTween; // 0x38
	private static DelegateBridge __Hotfix0_ShowAlpha; // 0x40
	private static DelegateBridge __Hotfix0_ShowChar; // 0x48
	private static DelegateBridge __Hotfix0_SendItemVoucherRequest; // 0x50
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x58
	private static DelegateBridge __Hotfix0_ShowGachaEffect; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2d25638 VA: 0x759533d638
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d256a0 VA: 0x759533d6a0
	protected override Void OnEnter() { }
	// RVA: 0x2d25bb0 VA: 0x759533dbb0
	public Void OnUseClick() { }
	// RVA: 0x2d25f00 VA: 0x759533df00
	protected override Void OnExit() { }
	// RVA: 0x2d25f7c VA: 0x759533df7c
	public Void OnDetailClick() { }
	// RVA: 0x2d259c4 VA: 0x759533d9c4
	public Void SendGetItem() { }
	// RVA: 0x2d257d8 VA: 0x759533d7d8
	public Void SendGetChar() { }
	// RVA: 0x2d260f4 VA: 0x759533e0f4
	private Void _ResetTween() { }
	// RVA: 0x2d26194 VA: 0x759533e194
	public Void ShowAlpha() { }
	// RVA: 0x2d26280 VA: 0x759533e280
	public Void ShowChar(CharGachaVoucherData info) { }
	// RVA: 0x2d25ce8 VA: 0x759533dce8
	public Void SendItemVoucherRequest() { }
	// RVA: 0x2d26354 VA: 0x759533e354
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d265b8 VA: 0x759533e5b8
	public Void ShowGachaEffect(GachaResult[] gachaResultList, Boolean isAdvanced, Boolean isSkippable) { }
	// RVA: 0x2d26a64 VA: 0x759533ea64
	public Void .ctor() { }
	// RVA: 0x2d26b40 VA: 0x759533eb40
	private Void <SendGetItem>b__10_0(VoucherItemDetailResponse response) { }
	// RVA: 0x2d26b90 VA: 0x759533eb90
	private Void <SendGetChar>b__11_0(VoucherCharDetailResponse response) { }
	// RVA: 0x2d26bd0 VA: 0x759533ebd0
	private Void <SendItemVoucherRequest>b__16_0(useCharGachaVoucherResponse response) { }
	// RVA: 0x2d26c3c VA: 0x759533ec3c
	private Void <RegisterToDataListener>b__17_0(IStateBean stateBean) { }
	// RVA: 0x2d26d40 VA: 0x759533ed40
	private Void <RegisterToDataListener>b__17_1(IStateBean stateBean) { }
	// RVA: 0x2d26ddc VA: 0x759533eddc
	private Void <RegisterToDataListener>b__17_2(IStateBean stateBean) { }
	// RVA: 0x2d26ed0 VA: 0x759533eed0
	private IStateBean <>xLuaBaseProxy_GetCacheBean() { }
	// RVA: 0x2d26f3c VA: 0x759533ef3c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d26f40 VA: 0x759533ef40
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2d26f48 VA: 0x759533ef48
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```