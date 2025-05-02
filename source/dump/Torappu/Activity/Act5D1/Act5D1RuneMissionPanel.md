# Act5D1RuneMissionPanel

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `ScrollRect _missionList`

- `Transform _contentRoot`

- `Act5D1RuneMissionItem _itemPrefab`

- `Text _remainHours`

- `Text _remainMinutes`

- `Act5D1RuneMissionState <ownerState>k__BackingField`


## Properties

- `Act5D1RuneMissionState ownerState`


## Methods

- `Act5D1RuneMissionState get_ownerState()`

- `Void set_ownerState(Act5D1RuneMissionState)`

- `Void SynContent(List`1, Act5D1RuneMissionState)`

- `Void Refresh()`

- `Void _AppendMissions(List`1, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
internal class Act5D1RuneMissionPanel : MonoBehaviour, IHotfixable
{
	private ScrollRect _missionList; // 0x18
	private Transform _contentRoot; // 0x20
	private Act5D1RuneMissionItem _itemPrefab; // 0x28
	private Text _remainHours; // 0x30
	private Text _remainMinutes; // 0x38
	private List`1 m_missionGrps; // 0x40
	private Act5D1RuneMissionState <ownerState>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_ownerState; // 0x0
	private static DelegateBridge __Hotfix0_set_ownerState; // 0x8
	private static DelegateBridge __Hotfix0_SynContent; // 0x10
	private static DelegateBridge __Hotfix0_Refresh; // 0x18
	private static DelegateBridge __Hotfix0__AppendMissions; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Act5D1RuneMissionState ownerState { get; set; }

	// RVA: 0x31d2f14 VA: 0x75957eaf14
	public Act5D1RuneMissionState get_ownerState() { }
	// RVA: 0x31d3aa4 VA: 0x75957ebaa4
	private Void set_ownerState(Act5D1RuneMissionState value) { }
	// RVA: 0x31d3b28 VA: 0x75957ebb28
	public Void SynContent(List`1 missionGrps, Act5D1RuneMissionState owner) { }
	// RVA: 0x31d32c0 VA: 0x75957eb2c0
	public Void Refresh() { }
	// RVA: 0x31d3bc8 VA: 0x75957ebbc8
	private Void _AppendMissions(List`1 missions, ref Int32 pos) { }
	// RVA: 0x31d3da8 VA: 0x75957ebda8
	public Void .ctor() { }
}
```