# Act4D0MileStoneGridAdapter

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `UIStringEvent _storyEvent`

- `UIStringEvent _itemEvent`

- `GameObject _mileStoneItem`

- `String focusCharId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0MileStoneGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private UIStringEvent _storyEvent; // 0x68
	private UIStringEvent _itemEvent; // 0x70
	private GameObject _mileStoneItem; // 0x78
	public String focusCharId; // 0x80
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31e0938 VA: 0x75957f8938
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x31e0a28 VA: 0x75957f8a28
	public override Void UpdateView(Int32 position, GameObject view, MileStoneItemHolder holder, Act4D0MileStoneViewModel data) { }
	// RVA: 0x31e0fdc VA: 0x75957f8fdc
	public Void .ctor() { }
}
```