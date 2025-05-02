# HomeAPUseApItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Text _detailText`

- `Text _restoreAP`

- `SimpleLayoutContent _itemLayout`

- `Single _scaleFactor`

- `UnityEvent _refreshEvent`

- `ItemRepoActionPointViewModelWithBuyApCount apProperty`

- `APItemAdapter m_itemAdapter`

- `UIItemCard m_itemCard`

- `Boolean m_initCardFlag`


## Methods

- `Void ClickItem(Int32)`

- `Void CleanItem(Int32)`

- `Boolean LongPress(Int32)`

- `Void CleanAll()`

- `Void SendUseAPItem()`

- `Void _InitData()`

- `Void RenderCurrentItem()`

- `Void Render(Int32)`

- `Void RefreshInfo(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAPUseApItemView : MonoBehaviour, IHotfixable
{
	private Text _detailText; // 0x18
	private Text _restoreAP; // 0x20
	private SimpleLayoutContent _itemLayout; // 0x28
	private Single _scaleFactor; // 0x30
	private UnityEvent _refreshEvent; // 0x38
	public ItemRepoActionPointViewModelWithBuyApCount apProperty; // 0x40
	public Action`1 onClick; // 0x48
	private APItemAdapter m_itemAdapter; // 0x50
	private List`1 m_viewModelList; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private Boolean m_initCardFlag; // 0x68
	private static DelegateBridge __Hotfix0_ClickItem; // 0x0
	private static DelegateBridge __Hotfix0_CleanItem; // 0x8
	private static DelegateBridge __Hotfix0_LongPress; // 0x10
	private static DelegateBridge __Hotfix0_CleanAll; // 0x18
	private static DelegateBridge __Hotfix0_SendUseAPItem; // 0x20
	private static DelegateBridge __Hotfix0__InitData; // 0x28
	private static DelegateBridge __Hotfix0_RenderCurrentItem; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x282ae80 VA: 0x7594e42e80
	public Void ClickItem(Int32 selectIndex) { }
	// RVA: 0x282b268 VA: 0x7594e43268
	public Void CleanItem(Int32 selectIndex) { }
	// RVA: 0x282b330 VA: 0x7594e43330
	public Boolean LongPress(Int32 selectIndex) { }
	// RVA: 0x282b4cc VA: 0x7594e434cc
	public Void CleanAll() { }
	// RVA: 0x282b5b0 VA: 0x7594e435b0
	public Void SendUseAPItem() { }
	// RVA: 0x282b870 VA: 0x7594e43870
	private Void _InitData() { }
	// RVA: 0x282afb8 VA: 0x7594e42fb8
	public Void RenderCurrentItem() { }
	// RVA: 0x282b948 VA: 0x7594e43948
	public Void Render(Int32 requireAp) { }
	// RVA: 0x282bcd4 VA: 0x7594e43cd4
	public Void RefreshInfo(Int32 position) { }
	// RVA: 0x282bd68 VA: 0x7594e43d68
	public Void .ctor() { }
}
```