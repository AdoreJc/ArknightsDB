# Act1BossRushMileStoneItemGridAdapter

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `GameObject _mileStoneItem`


## Methods

- `Void set_onItemClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMileStoneItemGridAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _mileStoneItem; // 0x68
	private Action`1 <onItemClick>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x31918f4 VA: 0x75957a98f4
	private Action`1 get_onItemClick() { }
	// RVA: 0x319195c VA: 0x75957a995c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x31919e0 VA: 0x75957a99e0
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x3191b04 VA: 0x75957a9b04
	public override Void UpdateView(Int32 position, GameObject view, Act1BossRushMileStoneItemHolder holder, Act1BossRushMileStoneItemViewModel data) { }
	// RVA: 0x3191f80 VA: 0x75957a9f80
	public Void .ctor() { }
}
```