# Act5D0MissionGridAdapter

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `UIStringEvent _itemEvent`

- `GameObject _missionItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0MissionGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private UIStringEvent _itemEvent; // 0x68
	public GameObject _missionItem; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31c0a7c VA: 0x75957d8a7c
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x31c0b6c VA: 0x75957d8b6c
	public override Void UpdateView(Int32 position, GameObject view, MissionItemHolder holder, Act5D0MissionViewModel data) { }
	// RVA: 0x31c0d34 VA: 0x75957d8d34
	public Void .ctor() { }
}
```