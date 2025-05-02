# Act3D0MileStoneGridAdapter

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `UIStringEvent clickEvent`

- `GameObject _mileStoneItem`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MileStoneGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	public UIStringEvent clickEvent; // 0x68
	public GameObject _mileStoneItem; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32351cc VA: 0x759584d1cc
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x32352bc VA: 0x759584d2bc
	public override Void UpdateView(Int32 position, GameObject view, MileStoneItemHolder holder, Act3D0MileStoneViewModel data) { }
	// RVA: 0x3235c44 VA: 0x759584dc44
	public Void .ctor() { }
}
```