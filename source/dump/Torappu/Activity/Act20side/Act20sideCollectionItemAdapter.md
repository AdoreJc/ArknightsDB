# Act20sideCollectionItemAdapter

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCommonCarCompItemView _itemPrefab`

- `String <selectedItemId>k__BackingField`


## Properties

- `String selectedItemId`


## Methods

- `String get_selectedItemId()`

- `Void set_selectedItemId(String)`

- `Void set_onItemClicked(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCollectionItemAdapter : RecycleLoopScrollAdapter`2
{
	private Act20sideCommonCarCompItemView _itemPrefab; // 0x68
	private String <selectedItemId>k__BackingField; // 0x70
	private Action`1 <onItemClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_selectedItemId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedItemId; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private String selectedItemId { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x32fe0b8 VA: 0x75959160b8
	private String get_selectedItemId() { }
	// RVA: 0x32fe120 VA: 0x7595916120
	public Void set_selectedItemId(String value) { }
	// RVA: 0x32fe1a4 VA: 0x75959161a4
	private Action`1 get_onItemClicked() { }
	// RVA: 0x32fe20c VA: 0x759591620c
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x32fe290 VA: 0x7595916290
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, Act20sideCollectionItemViewModel data) { }
	// RVA: 0x32fe694 VA: 0x7595916694
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x32fe82c VA: 0x759591682c
	public Void .ctor() { }
}
```