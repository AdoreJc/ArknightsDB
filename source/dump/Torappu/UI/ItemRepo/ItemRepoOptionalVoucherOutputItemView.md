# ItemRepoOptionalVoucherOutputItemView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Transform _itemCardContainer`

- `Single _itemScale`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void ApplyData(UIItemViewModel)`

- `Void _InitIfNot()`

- `Void _OnItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherOutputItemView : MonoBehaviour, IHotfixable
{
	private Transform _itemCardContainer; // 0x18
	private Single _itemScale; // 0x20
	private UIItemCard m_itemCard; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0_ApplyData; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d365c4 VA: 0x759534e5c4
	public Void ApplyData(UIItemViewModel viewModel) { }
	// RVA: 0x2d3665c VA: 0x759534e65c
	private Void _InitIfNot() { }
	// RVA: 0x2d36898 VA: 0x759534e898
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x2d369a0 VA: 0x759534e9a0
	public Void .ctor() { }
}
```