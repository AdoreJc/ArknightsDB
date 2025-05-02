# BuildingManufactStationView

**Namespace:** `Torappu.Building.UI.Manufact`


## Fields

- `SimpleLayoutContent _charLayout`

- `MRoomViewModel m_viewModel`

- `BuildingCharAvatarStationAdatper m_adapter`

- `Boolean m_isInited`


## Properties

- `Int32 finalMaxCharNum`

- `Int32 curMaxCharNum`

- `String slotId`

- `SimpleLayoutContent avatarContainer`


## Methods

- `Int32 get_finalMaxCharNum()`

- `Int32 get_curMaxCharNum()`

- `String get_slotId()`

- `SimpleLayoutContent get_avatarContainer()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Manufact
public class BuildingManufactStationView : DataBinder`1, IProvider
{
	private SimpleLayoutContent _charLayout; // 0x20
	private MRoomViewModel m_viewModel; // 0x28
	private BuildingCharAvatarStationAdatper m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	public Action`2 onCharClicked; // 0x40
	private static DelegateBridge __Hotfix0_get_finalMaxCharNum; // 0x0
	private static DelegateBridge __Hotfix0_get_curMaxCharNum; // 0x8
	private static DelegateBridge __Hotfix0_get_stationedChars; // 0x10
	private static DelegateBridge __Hotfix0_Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.get_onCharClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_slotId; // 0x20
	private static DelegateBridge __Hotfix0_get_avatarContainer; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 finalMaxCharNum { get; }
	public Int32 curMaxCharNum { get; }
	public BuildingCharModel[] stationedChars { get; }
	private Action`2 Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.onCharClicked { get; }
	public String slotId { get; }
	public SimpleLayoutContent avatarContainer { get; }

	// RVA: 0x3e0e810 VA: 0x7596426810
	public Int32 get_finalMaxCharNum() { }
	// RVA: 0x3e0e894 VA: 0x7596426894
	public Int32 get_curMaxCharNum() { }
	// RVA: 0x3e0e918 VA: 0x7596426918
	public BuildingCharModel[] get_stationedChars() { }
	// RVA: 0x3e0e998 VA: 0x7596426998
	private Action`2 Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.get_onCharClicked() { }
	// RVA: 0x3e0ea00 VA: 0x7596426a00
	public String get_slotId() { }
	// RVA: 0x3e0ea94 VA: 0x7596426a94
	public SimpleLayoutContent get_avatarContainer() { }
	// RVA: 0x3e0eafc VA: 0x7596426afc
	public override Void OnValueChanged(MRoomViewPropety property) { }
	// RVA: 0x3e0ebf8 VA: 0x7596426bf8
	public Void .ctor() { }
}
```