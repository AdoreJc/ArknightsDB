# Act12D6MileStoneGridAdapter

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `UIStringEvent _itemEvent`

- `GameObject _mileStoneItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6MileStoneGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private UIStringEvent _itemEvent; // 0x68
	private GameObject _mileStoneItem; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x34764a4 VA: 0x7595a8e4a4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x3476594 VA: 0x7595a8e594
	public override Void UpdateView(Int32 position, GameObject view, MileStoneItemHolder holder, Act12D6MileStoneViewModel data) { }
	// RVA: 0x3476a54 VA: 0x7595a8ea54
	public Void .ctor() { }
}
```