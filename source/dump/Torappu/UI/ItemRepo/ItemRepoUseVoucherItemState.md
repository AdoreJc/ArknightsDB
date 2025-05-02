# ItemRepoUseVoucherItemState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoUseVoucherItemStateBean _stateBean`

- `Int32 m_currentBuyCount`

- `Text _countText`

- `Text _detailText`

- `Image _itemImage`

- `Image _backImage`

- `Text _currentCount`


## Methods

- `Void InitRender()`

- `Void CheckAndRender(Int32)`

- `Void MinusCount()`

- `Void AddCount()`

- `Void ToMaxCount()`

- `Void ToMinCount()`

- `Void SendItemVoucherRequest()`

- `Void <SendItemVoucherRequest>b__16_0(UseMaterialVoucherResponse)`

- `Void <SendItemVoucherRequest>b__16_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoUseVoucherItemState : PopupFloatState
{
	public const Int32 USE_MAX_COUNT; // 0x0
	private ItemRepoUseVoucherItemStateBean _stateBean; // 0x70
	private Int32 m_currentBuyCount; // 0x78
	private Text _countText; // 0x80
	private Text _detailText; // 0x88
	private Image _itemImage; // 0x90
	private Image _backImage; // 0x98
	private Text _currentCount; // 0xa0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_InitRender; // 0x10
	private static DelegateBridge __Hotfix0_CheckAndRender; // 0x18
	private static DelegateBridge __Hotfix0_MinusCount; // 0x20
	private static DelegateBridge __Hotfix0_AddCount; // 0x28
	private static DelegateBridge __Hotfix0_ToMaxCount; // 0x30
	private static DelegateBridge __Hotfix0_ToMinCount; // 0x38
	private static DelegateBridge __Hotfix0_SendItemVoucherRequest; // 0x40
	private static DelegateBridge __Hotfix0__ReceiveItems; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2d23dec VA: 0x759533bdec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d23e54 VA: 0x759533be54
	protected override Void OnEnter() { }
	// RVA: 0x2d23fb4 VA: 0x759533bfb4
	public Void InitRender() { }
	// RVA: 0x2d241d4 VA: 0x759533c1d4
	public Void CheckAndRender(Int32 count) { }
	// RVA: 0x2d243c0 VA: 0x759533c3c0
	public Void MinusCount() { }
	// RVA: 0x2d24430 VA: 0x759533c430
	public Void AddCount() { }
	// RVA: 0x2d244a0 VA: 0x759533c4a0
	public Void ToMaxCount() { }
	// RVA: 0x2d24528 VA: 0x759533c528
	public Void ToMinCount() { }
	// RVA: 0x2d24594 VA: 0x759533c594
	public Void SendItemVoucherRequest() { }
	// RVA: 0x2d247e4 VA: 0x759533c7e4
	private static IEnumerator _ReceiveItems(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x2d248e8 VA: 0x759533c8e8
	public Void .ctor() { }
	// RVA: 0x2d24960 VA: 0x759533c960
	private Void <SendItemVoucherRequest>b__16_0(UseMaterialVoucherResponse response) { }
	// RVA: 0x2d24a2c VA: 0x759533ca2c
	private Void <SendItemVoucherRequest>b__16_1() { }
	// RVA: 0x2d24afc VA: 0x759533cafc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```