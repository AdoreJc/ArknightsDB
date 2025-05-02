# BattleFinishRuneGridAdapter

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `UIStringEvent _itemEvent`

- `GameObject _item`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class BattleFinishRuneGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private UIStringEvent _itemEvent; // 0x68
	private GameObject _item; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c8f38 VA: 0x75957e0f38
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x31c9028 VA: 0x75957e1028
	public override Void UpdateView(Int32 position, GameObject view, BattleFinishRuneItemHolder holder, PackedRuneData data) { }
	// RVA: 0x31c92a0 VA: 0x75957e12a0
	public Void .ctor() { }
}
```