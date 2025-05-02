# ItemRepoUseApSupplyItem

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoActionPointViewModelWithBuyApCount _buyApCount`

- `Text _buyCount`

- `Text _buyDetail`

- `Text _cannotUseMore`

- `UnityEvent _dismissAction`

- `GameObject _canUsePart`

- `GameObject _cannotUsePart`

- `AddApNotifyView _notifyView`

- `Text _title`

- `Text _itemCount`

- `GameObject _onTimePart`

- `Text _onTimeText`

- `CanvasGroup _buyCanvas`

- `UIItemViewModel m_cacheViewModel`

- `Int32 m_currentBuyCount`


## Methods

- `Int32 GetMaxCount()`

- `Void RenderAp(UIItemViewModel)`

- `Void RenderCurrentBuyCount(Int32)`

- `Void CheckAndRender(Int32)`

- `Void MinusCount()`

- `Void AddCount()`

- `Void ToMaxCount()`

- `Void ToMinCount()`

- `Void OnSendService()`

- `Void SendUseApItemService(UIItemViewModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoUseApSupplyItem : MonoBehaviour, IHotfixable
{
	private ItemRepoActionPointViewModelWithBuyApCount _buyApCount; // 0x18
	private Text _buyCount; // 0x20
	private Text _buyDetail; // 0x28
	private Text _cannotUseMore; // 0x30
	private UnityEvent _dismissAction; // 0x38
	private GameObject _canUsePart; // 0x40
	private GameObject _cannotUsePart; // 0x48
	private AddApNotifyView _notifyView; // 0x50
	private Text _title; // 0x58
	private Text _itemCount; // 0x60
	private GameObject _onTimePart; // 0x68
	private Text _onTimeText; // 0x70
	private CanvasGroup _buyCanvas; // 0x78
	private UIItemViewModel m_cacheViewModel; // 0x80
	private Int32 m_currentBuyCount; // 0x88
	private static DelegateBridge __Hotfix0_GetMaxCount; // 0x0
	private static DelegateBridge __Hotfix0_RenderAp; // 0x8
	private static DelegateBridge __Hotfix0_RenderCurrentBuyCount; // 0x10
	private static DelegateBridge __Hotfix0_CheckAndRender; // 0x18
	private static DelegateBridge __Hotfix0_MinusCount; // 0x20
	private static DelegateBridge __Hotfix0_AddCount; // 0x28
	private static DelegateBridge __Hotfix0_ToMaxCount; // 0x30
	private static DelegateBridge __Hotfix0_ToMinCount; // 0x38
	private static DelegateBridge __Hotfix0_OnSendService; // 0x40
	private static DelegateBridge __Hotfix0_SendUseApItemService; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2d39ac4 VA: 0x7595351ac4
	public Int32 GetMaxCount() { }
	// RVA: 0x2d39c10 VA: 0x7595351c10
	public Void RenderAp(UIItemViewModel itemViewModel) { }
	// RVA: 0x2d3a008 VA: 0x7595352008
	public Void RenderCurrentBuyCount(Int32 buyCount) { }
	// RVA: 0x2d3a2c4 VA: 0x75953522c4
	public Void CheckAndRender(Int32 newCount) { }
	// RVA: 0x2d3a358 VA: 0x7595352358
	public Void MinusCount() { }
	// RVA: 0x2d3a3c8 VA: 0x75953523c8
	public Void AddCount() { }
	// RVA: 0x2d3a438 VA: 0x7595352438
	public Void ToMaxCount() { }
	// RVA: 0x2d3a4ac VA: 0x75953524ac
	public Void ToMinCount() { }
	// RVA: 0x2d3a518 VA: 0x7595352518
	public Void OnSendService() { }
	// RVA: 0x2d3a588 VA: 0x7595352588
	public Void SendUseApItemService(UIItemViewModel itemViewModel, Int32 count) { }
	// RVA: 0x2d3a980 VA: 0x7595352980
	public Void .ctor() { }
}
```