# MissionDetailView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `RectTransform _bound`

- `RectTransform _panelLocal`

- `RectTransform _taskContainer`

- `MissionProgressBar _progressBar`

- `Text _descrption`

- `Transform _constrain0`

- `Transform _constrain1`

- `GameObject m_missionTask`

- `MissionViewModel m_viewModel`


## Methods

- `Vector3 PositionConstrain(Vector3, Vector3, Vector3)`

- `Void HideView()`

- `Void _ApplyMissionView(MissionViewModel)`

- `Void _UpdateLayout(GameObject)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionDetailView : PageSingleComponent
{
	private RectTransform _bound; // 0x20
	private RectTransform _panelLocal; // 0x28
	private RectTransform _taskContainer; // 0x30
	private MissionProgressBar _progressBar; // 0x38
	private Text _descrption; // 0x40
	private Transform _constrain0; // 0x48
	private Transform _constrain1; // 0x50
	private GameObject m_missionTask; // 0x58
	private MissionViewModel m_viewModel; // 0x60
	private static DelegateBridge __Hotfix0_RegisterFocusItem; // 0x0
	private static DelegateBridge __Hotfix0_PositionConstrain; // 0x8
	private static DelegateBridge __Hotfix0_HideView; // 0x10
	private static DelegateBridge __Hotfix0__ApplyMissionView; // 0x18
	private static DelegateBridge __Hotfix0__UpdateLayout; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2742714 VA: 0x7594d5a714
	public static Void RegisterFocusItem(GameObject itemCard, MissionViewModel missionData) { }
	// RVA: 0x2742a78 VA: 0x7594d5aa78
	private Vector3 PositionConstrain(Vector3 target, Vector3 p0, Vector3 p1) { }
	// RVA: 0x2742b8c VA: 0x7594d5ab8c
	public Void HideView() { }
	// RVA: 0x27429c0 VA: 0x7594d5a9c0
	private Void _ApplyMissionView(MissionViewModel missionData) { }
	// RVA: 0x2742814 VA: 0x7594d5a814
	private Void _UpdateLayout(GameObject taskObj) { }
	// RVA: 0x2742d08 VA: 0x7594d5ad08
	public Void .ctor() { }
}
```