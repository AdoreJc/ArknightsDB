# MileStoneGridAdapter

**Namespace:** `Torappu.Activity`


## Fields

- `UIStringEvent _itemEvent`

- `GameObject _mileStoneItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class MileStoneGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private UIStringEvent _itemEvent; // 0x68
	private GameObject _mileStoneItem; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30c5d84 VA: 0x75956ddd84
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x30c5e74 VA: 0x75956dde74
	public override Void UpdateView(Int32 position, GameObject view, MileStoneItemHolder holder, MileStoneViewModel data) { }
	// RVA: 0x30c5fc4 VA: 0x75956ddfc4
	public Void .ctor() { }
}
```