# MedalBarListRecycleList

**Namespace:** `Torappu.UI.Medal`


## Fields

- `UIMedalEvent _clickMedalEvent`

- `UIStringEvent _clickToGroupEvent`

- `UIStringEvent _clickToMedalEvent`

- `GameObject _emptyFlag`

- `GameObject _medalObj`


## Methods

- `Void OnMedalClick(String)`

- `Void <>xLuaBaseProxy_OnDataSourceChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalBarListRecycleList : RecycleLoopScrollAdapter, IHotfixable
{
	private UIMedalEvent _clickMedalEvent; // 0x58
	private UIStringEvent _clickToGroupEvent; // 0x60
	private UIStringEvent _clickToMedalEvent; // 0x68
	private GameObject _emptyFlag; // 0x70
	public List`1 viewModelList; // 0x78
	public GameObject _medalObj; // 0x80
	private static DelegateBridge __Hotfix0_get_currentViewModelList; // 0x0
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x8
	private static DelegateBridge __Hotfix0_OnMedalClick; // 0x10
	private static DelegateBridge __Hotfix0_OnDataSourceChanged; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 currentViewModelList { get; }
	public override Int32 totalCount { get; }

	// RVA: 0x279e458 VA: 0x7594db6458
	public List`1 get_currentViewModelList() { }
	// RVA: 0x279e4c0 VA: 0x7594db64c0
	public override Int32 get_totalCount() { }
	// RVA: 0x279e544 VA: 0x7594db6544
	public Void OnMedalClick(String medalId) { }
	// RVA: 0x279e658 VA: 0x7594db6658
	protected override Void OnDataSourceChanged(Boolean forceRebuild) { }
	// RVA: 0x279e704 VA: 0x7594db6704
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x279e9a4 VA: 0x7594db69a4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x279ea94 VA: 0x7594db6a94
	public Void .ctor() { }
	// RVA: 0x279eb04 VA: 0x7594db6b04
	private Void <>xLuaBaseProxy_OnDataSourceChanged(Boolean P0) { }
}
```