# SandboxV2RacerTempInventoryInfoView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RacerInventoryDetailView _prefabDetail`

- `RectTransform _containerDetail`

- `GameObject _panelReleaseAllBtn`

- `GameObject _panelRegisterBtn`

- `Boolean m_hasInited`

- `SandboxV2RacerInventoryDetailView m_detailView`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnReleaseAllClicked()`

- `Void EventOnRegisterClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerTempInventoryInfoView : DataBinder`1, IHotfixable
{
	private SandboxV2RacerInventoryDetailView _prefabDetail; // 0x20
	private RectTransform _containerDetail; // 0x28
	private GameObject _panelReleaseAllBtn; // 0x30
	private GameObject _panelRegisterBtn; // 0x38
	private Boolean m_hasInited; // 0x40
	private SandboxV2RacerInventoryDetailView m_detailView; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnReleaseAllClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnRegisterClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x25f4064 VA: 0x7594c0c064
	public override Void OnValueChanged(SandboxV2RacerTempInventoryProperty property) { }
	// RVA: 0x25f4340 VA: 0x7594c0c340
	public Void EventOnReleaseAllClicked() { }
	// RVA: 0x25f43e4 VA: 0x7594c0c3e4
	public Void EventOnRegisterClicked() { }
	// RVA: 0x25f41cc VA: 0x7594c0c1cc
	private Void _InitIfNot() { }
	// RVA: 0x25f4488 VA: 0x7594c0c488
	public Void .ctor() { }
}
```