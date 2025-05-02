# Act12sideMilestoneListAdapter

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `GameObject _itemTemplate`


## Methods

- `Void set_onMilestoneClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMilestoneListAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _itemTemplate; // 0x68
	private Action`1 <onMilestoneClick>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onMilestoneClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onMilestoneClick; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onMilestoneClick { get; set; }

	// RVA: 0x3465acc VA: 0x7595a7dacc
	private Action`1 get_onMilestoneClick() { }
	// RVA: 0x3465b34 VA: 0x7595a7db34
	public Void set_onMilestoneClick(Action`1 value) { }
	// RVA: 0x3465bb8 VA: 0x7595a7dbb8
	public override Void UpdateView(Int32 position, GameObject view, Act12sideMilestoneItemHolder holder, Act12sideMilestoneItemModel data) { }
	// RVA: 0x3465cf4 VA: 0x7595a7dcf4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x3465db0 VA: 0x7595a7ddb0
	public Void .ctor() { }
}
```