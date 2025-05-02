# TemplateMissionAdapter

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `UIStringEvent onMissionGetRewardClick`

- `GameObject _itemObj`

- `MonoBehaviour _plugin`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateMissionAdapter : RecycleLoopScrollAdapter
{
	public List`1 missionItemList; // 0x58
	public UIStringEvent onMissionGetRewardClick; // 0x60
	private GameObject _itemObj; // 0x68
	private MonoBehaviour _plugin; // 0x70
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x30a9464 VA: 0x75956c1464
	public override Int32 get_totalCount() { }
	// RVA: 0x30a94e4 VA: 0x75956c14e4
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x30a96fc VA: 0x75956c16fc
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x30a97ec VA: 0x75956c17ec
	public Void .ctor() { }
}
```