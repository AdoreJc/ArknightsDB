# Act9D0MissionGroupAdapter

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `GameObject _missionObjPrefab`

- `UIStringEvent _onMissionObjClicked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0MissionGroupAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private GameObject _missionObjPrefab; // 0x68
	private UIStringEvent _onMissionObjClicked; // 0x70
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31a5f84 VA: 0x75957bdf84
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x31a6040 VA: 0x75957be040
	public override Void UpdateView(Int32 position, GameObject view, MissionObjViewHolder holder, MissionViewModel data) { }
	// RVA: 0x31a6830 VA: 0x75957be830
	public Void .ctor() { }
}
```