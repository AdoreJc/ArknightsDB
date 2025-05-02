# StageUseApItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _container`

- `UIItemCard _itemCard`

- `Text _detailText`

- `Text _restoreAP`

- `SimpleLayoutContent _itemLayout`

- `Single _scaleFactor`

- `UnityEvent _refreshEvent`

- `APItemAdapter m_itemAdapter`

- `UIItemCard m_itemCard`

- `Boolean m_initCardFlag`


## Methods

- `Void ClickItem(Int32)`

- `Void _InitData()`

- `Void RenderCurrentItem(String)`

- `Void _InitItemCard()`

- `Void Render()`

- `Void RefreshInfo(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageUseApItemView : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private UIItemCard _itemCard; // 0x20
	private Text _detailText; // 0x28
	private Text _restoreAP; // 0x30
	private SimpleLayoutContent _itemLayout; // 0x38
	private Single _scaleFactor; // 0x40
	private UnityEvent _refreshEvent; // 0x48
	private APItemAdapter m_itemAdapter; // 0x50
	private List`1 m_viewModelList; // 0x58
	private UIItemCard m_itemCard; // 0x60
	private Boolean m_initCardFlag; // 0x68
	private static DelegateBridge __Hotfix0_ClickItem; // 0x0
	private static DelegateBridge __Hotfix0__InitData; // 0x8
	private static DelegateBridge __Hotfix0_RenderCurrentItem; // 0x10
	private static DelegateBridge __Hotfix0__InitItemCard; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_RefreshInfo; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f8b178 VA: 0x75955a3178
	public Void ClickItem(Int32 selectIndex) { }
	// RVA: 0x2f8b494 VA: 0x75955a3494
	private Void _InitData() { }
	// RVA: 0x2f8b25c VA: 0x75955a325c
	public Void RenderCurrentItem(String itemId) { }
	// RVA: 0x2f8b56c VA: 0x75955a356c
	private Void _InitItemCard() { }
	// RVA: 0x2f8b704 VA: 0x75955a3704
	public Void Render() { }
	// RVA: 0x2f8ba54 VA: 0x75955a3a54
	public Void RefreshInfo(Int32 position) { }
	// RVA: 0x2f8bae8 VA: 0x75955a3ae8
	public Void .ctor() { }
}
```