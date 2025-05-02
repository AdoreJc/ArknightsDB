# MissionSinglePage

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionModel <stateBean>k__BackingField`

- `Boolean m_needRefresh`

- `Boolean <isDisplay>k__BackingField`


## Properties

- `MissionModel stateBean`

- `Boolean isDisplay`


## Methods

- `MissionModel get_stateBean()`

- `Void set_stateBean(MissionModel)`

- `Boolean get_isDisplay()`

- `Void set_isDisplay(Boolean)`

- `Void InitData(MissionModel)`

- `Void RefreshData(MissionModel)`

- `Void ToggleDisplay(Boolean, Boolean)`

- `Boolean HasMissionType(MissionType)`

- `Void _OnDislay()`

- `Void _TryTriggerRefreshView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionSinglePage : MonoBehaviour, IHotfixable
{
	protected MissionType[] _missionType; // 0x18
	private MissionModel <stateBean>k__BackingField; // 0x20
	private Boolean m_needRefresh; // 0x28
	private Boolean <isDisplay>k__BackingField; // 0x29
	private static DelegateBridge __Hotfix0_get_stateBean; // 0x0
	private static DelegateBridge __Hotfix0_set_stateBean; // 0x8
	private static DelegateBridge __Hotfix0_get_isDisplay; // 0x10
	private static DelegateBridge __Hotfix0_set_isDisplay; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_IsToBeShown; // 0x28
	private static DelegateBridge __Hotfix0_RefreshData; // 0x30
	private static DelegateBridge __Hotfix0_RefreshView; // 0x38
	private static DelegateBridge __Hotfix0_ToggleDisplay; // 0x40
	private static DelegateBridge __Hotfix0_HasMissionType; // 0x48
	private static DelegateBridge __Hotfix0__OnDislay; // 0x50
	private static DelegateBridge __Hotfix0__TryTriggerRefreshView; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected MissionModel stateBean { get; set; }
	protected Boolean isDisplay { get; set; }

	// RVA: 0x2743e64 VA: 0x7594d5be64
	protected MissionModel get_stateBean() { }
	// RVA: 0x2743ecc VA: 0x7594d5becc
	private Void set_stateBean(MissionModel value) { }
	// RVA: 0x2743f50 VA: 0x7594d5bf50
	protected Boolean get_isDisplay() { }
	// RVA: 0x2743fb8 VA: 0x7594d5bfb8
	private Void set_isDisplay(Boolean value) { }
	// RVA: 0x2744038 VA: 0x7594d5c038
	public Void InitData(MissionModel stateBean) { }
	// RVA: 0x274416c VA: 0x7594d5c16c
	public virtual Boolean IsToBeShown(MissionModel stateBean) { }
	// RVA: 0x27441e8 VA: 0x7594d5c1e8
	public Void RefreshData(MissionModel stateBean) { }
	// RVA: 0x2744294 VA: 0x7594d5c294
	protected virtual Void RefreshView() { }
	// RVA: 0x27442f8 VA: 0x7594d5c2f8
	public Void ToggleDisplay(Boolean display, Boolean isInit) { }
	// RVA: 0x274443c VA: 0x7594d5c43c
	public Boolean HasMissionType(MissionType missionType) { }
	// RVA: 0x27443cc VA: 0x7594d5c3cc
	private Void _OnDislay() { }
	// RVA: 0x27440e4 VA: 0x7594d5c0e4
	private Void _TryTriggerRefreshView() { }
	// RVA: 0x27444f4 VA: 0x7594d5c4f4
	public Void .ctor() { }
}
```