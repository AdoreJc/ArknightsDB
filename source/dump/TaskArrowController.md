# TaskArrowController

**Namespace:** ` `


## Fields

- `SiracusaMapBigMapView m_closure`

- `SiracusaBigMapTaskArrow m_arrowPrefab`

- `RectTransform m_arrowContainer`


## Methods

- `Void UpdateData(SiracusaMapPanelMapViewModel)`

- `Void Tick()`

- `SiracusaBigMapTaskArrow _DequeueTaskInstOrCreate()`

- `Void _ClearPrevInstsAndSyncFromBindings()`

- `Void _UpdateBinding(TaskBindings)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TaskArrowController : IHotfixable
{
	private SiracusaMapBigMapView m_closure; // 0x10
	private SiracusaBigMapTaskArrow m_arrowPrefab; // 0x18
	private RectTransform m_arrowContainer; // 0x20
	private Queue`1 m_activeInsts; // 0x28
	private List`1 m_bindings; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge __Hotfix0_Tick; // 0x10
	private static DelegateBridge __Hotfix0__DequeueTaskInstOrCreate; // 0x18
	private static DelegateBridge __Hotfix0__ClearPrevInstsAndSyncFromBindings; // 0x20
	private static DelegateBridge __Hotfix0__UpdateBinding; // 0x28


	// RVA: 0x240f1b4 VA: 0x7594a271b4
	public Void .ctor(SiracusaMapBigMapView closure) { }
	// RVA: 0x240e6cc VA: 0x7594a266cc
	public Void UpdateData(SiracusaMapPanelMapViewModel viewModel) { }
	// RVA: 0x240ea60 VA: 0x7594a26a60
	public Void Tick() { }
	// RVA: 0x2410f60 VA: 0x7594a28f60
	private SiracusaBigMapTaskArrow _DequeueTaskInstOrCreate() { }
	// RVA: 0x2411068 VA: 0x7594a29068
	private Void _ClearPrevInstsAndSyncFromBindings() { }
	// RVA: 0x2411234 VA: 0x7594a29234
	private Void _UpdateBinding(TaskBindings binding) { }
}
```