# GroceryMileStoneState

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GroceryMileStoneView _view`

- `RectTransform _topMenu`

- `GroceryMileStoneStateBean m_stateBean`

- `Boolean m_hasInited`

- `String m_actId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnItemClick(String)`

- `Void _OnGetAllClick()`

- `Void _InitIfNot()`

- `Void _LoadData()`

- `Void _RefreshData()`

- `Void _OnBackBtnClicked()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryMileStoneState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_MSG_MILE_STONE_ITEM_CLICKED; // 0x0
	public const Int32 ON_MSG_MILE_STONE_ALL_CLICKED; // 0x0
	private GroceryMileStoneView _view; // 0x70
	private RectTransform _topMenu; // 0x78
	private GroceryMileStoneStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private String m_actId; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x20
	private static DelegateBridge __Hotfix0__OnGetAllClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__LoadData; // 0x38
	private static DelegateBridge __Hotfix0__RefreshData; // 0x40
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__OnBackBtnClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x28a98cc VA: 0x7594ec18cc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x28a9934 VA: 0x7594ec1934
	protected override Void OnEnter() { }
	// RVA: 0x28a9c1c VA: 0x7594ec1c1c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x28a9db0 VA: 0x7594ec1db0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x28a9e9c VA: 0x7594ec1e9c
	private Void _OnItemClick(String mileStoneId) { }
	// RVA: 0x28aa1e8 VA: 0x7594ec21e8
	private Void _OnGetAllClick() { }
	// RVA: 0x28a99b0 VA: 0x7594ec19b0
	private Void _InitIfNot() { }
	// RVA: 0x28a9abc VA: 0x7594ec1abc
	private Void _LoadData() { }
	// RVA: 0x28aa4e4 VA: 0x7594ec24e4
	private Void _RefreshData() { }
	// RVA: 0x28aa584 VA: 0x7594ec2584
	private static IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x28aa688 VA: 0x7594ec2688
	private Void _OnBackBtnClicked() { }
	// RVA: 0x28aa7e8 VA: 0x7594ec27e8
	public Void .ctor() { }
	// RVA: 0x28aa894 VA: 0x7594ec2894
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x28aa8bc VA: 0x7594ec28bc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x28aa8c4 VA: 0x7594ec28c4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```