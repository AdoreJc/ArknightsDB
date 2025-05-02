# FifthAnnivExploreMissionGroupAdapter

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `GameObject _missionObjHolderPrefab`

- `UIStringEvent _onMissionObjClicked`

- `UIStringEvent _onCollectAllBtnClicked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMissionGroupAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private GameObject _missionObjHolderPrefab; // 0x68
	private UIStringEvent _onMissionObjClicked; // 0x70
	private UIStringEvent _onCollectAllBtnClicked; // 0x78
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x292c720 VA: 0x7594f44720
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x292c7dc VA: 0x7594f447dc
	public override Void UpdateView(Int32 position, GameObject view, MissionObjViewHolder holder, MissionObjHolderViewModel data) { }
	// RVA: 0x292cbc4 VA: 0x7594f44bc4
	public Void .ctor() { }
}
```