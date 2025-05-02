# EnemyHandBookScrollListAdapter

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `GameObject _itemTemplate`

- `String <selectedId>k__BackingField`

- `Boolean <disableNewFlag>k__BackingField`


## Properties

- `String selectedId`

- `Boolean disableNewFlag`


## Methods

- `String get_selectedId()`

- `Void set_selectedId(String)`

- `Boolean get_disableNewFlag()`

- `Void set_disableNewFlag(Boolean)`

- `Void set_onItemClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookScrollListAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _itemTemplate; // 0x68
	private String <selectedId>k__BackingField; // 0x70
	private Boolean <disableNewFlag>k__BackingField; // 0x78
	private Action`1 <onItemClick>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_selectedId; // 0x0
	private static DelegateBridge __Hotfix0_set_selectedId; // 0x8
	private static DelegateBridge __Hotfix0_get_disableNewFlag; // 0x10
	private static DelegateBridge __Hotfix0_set_disableNewFlag; // 0x18
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x28
	private static DelegateBridge __Hotfix0_UpdateView; // 0x30
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String selectedId { get; set; }
	private Boolean disableNewFlag { get; set; }
	private Action`1 onItemClick { get; set; }

	// RVA: 0x2936be0 VA: 0x7594f4ebe0
	public String get_selectedId() { }
	// RVA: 0x2936c48 VA: 0x7594f4ec48
	public Void set_selectedId(String value) { }
	// RVA: 0x2936ccc VA: 0x7594f4eccc
	private Boolean get_disableNewFlag() { }
	// RVA: 0x2936d34 VA: 0x7594f4ed34
	public Void set_disableNewFlag(Boolean value) { }
	// RVA: 0x2936db4 VA: 0x7594f4edb4
	private Action`1 get_onItemClick() { }
	// RVA: 0x2936e1c VA: 0x7594f4ee1c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2936ea0 VA: 0x7594f4eea0
	public override Void UpdateView(Int32 position, GameObject view, EnemyHandBookScrollListItemHolder holder, EnemyHandBookEverViewModel data) { }
	// RVA: 0x2936fd0 VA: 0x7594f4efd0
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x293708c VA: 0x7594f4f08c
	public Void .ctor() { }
}
```