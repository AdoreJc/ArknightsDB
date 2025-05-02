# RoguelikeSacrificeViewScrollAdapter

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _itemPrefab`

- `Boolean <isInit>k__BackingField`

- `String <selectedItem>k__BackingField`


## Properties

- `Boolean isInit`

- `String selectedItem`


## Methods

- `Boolean get_isInit()`

- `Void set_isInit(Boolean)`

- `String get_selectedItem()`

- `Void set_selectedItem(String)`

- `Void set_onItemClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeViewScrollAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _itemPrefab; // 0x68
	private Boolean <isInit>k__BackingField; // 0x70
	private String <selectedItem>k__BackingField; // 0x78
	private Action`1 <onItemClick>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_isInit; // 0x0
	private static DelegateBridge __Hotfix0_set_isInit; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedItem; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedItem; // 0x18
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x28
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x30
	private static DelegateBridge __Hotfix0_UpdateView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isInit { get; set; }
	public String selectedItem { get; set; }
	private Action`1 onItemClick { get; set; }

	// RVA: 0x2ac2384 VA: 0x75950da384
	public Boolean get_isInit() { }
	// RVA: 0x2ac1c28 VA: 0x75950d9c28
	public Void set_isInit(Boolean value) { }
	// RVA: 0x2ac23ec VA: 0x75950da3ec
	public String get_selectedItem() { }
	// RVA: 0x2ac1ca8 VA: 0x75950d9ca8
	public Void set_selectedItem(String value) { }
	// RVA: 0x2ac2454 VA: 0x75950da454
	private Action`1 get_onItemClick() { }
	// RVA: 0x2ac1d2c VA: 0x75950d9d2c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2ac24bc VA: 0x75950da4bc
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2ac2578 VA: 0x75950da578
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, IRoguelikeSacrifice data) { }
	// RVA: 0x2ac26e8 VA: 0x75950da6e8
	public Void .ctor() { }
}
```