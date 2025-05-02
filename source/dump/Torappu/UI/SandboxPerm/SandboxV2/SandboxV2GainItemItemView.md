# SandboxV2GainItemItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _itemCardContainer`

- `SandboxV2ItemCard _itemCardPrefab`

- `Single _cardScale`

- `Boolean m_hasInited`

- `SandboxV2ItemCard m_itemCard`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void Render(Int32, UIItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2GainItemItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _itemCardContainer; // 0x18
	private SandboxV2ItemCard _itemCardPrefab; // 0x20
	private Single _cardScale; // 0x28
	private Boolean m_hasInited; // 0x2c
	private SandboxV2ItemCard m_itemCard; // 0x30
	private Action`1 <onItemClicked>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x25c8f9c VA: 0x7594be0f9c
	private Action`1 get_onItemClicked() { }
	// RVA: 0x25c9004 VA: 0x7594be1004
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x25c9088 VA: 0x7594be1088
	public Void Render(Int32 position, UIItemViewModel itemViewModel) { }
	// RVA: 0x25c9178 VA: 0x7594be1178
	private Void _InitIfNot() { }
	// RVA: 0x25c92a8 VA: 0x7594be12a8
	public Void .ctor() { }
}
```