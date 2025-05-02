# BuildingTradingStationView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `SimpleLayoutContent _charLayout`

- `TRoomViewModel m_viewModel`

- `BuildingCharAvatarStationAdatper m_adapter`

- `Boolean m_isInited`


## Properties

- `Int32 finalMaxCharNum`

- `Int32 curMaxCharNum`

- `SimpleLayoutContent avatarContainer`

- `String slotId`


## Methods

- `Int32 get_finalMaxCharNum()`

- `Int32 get_curMaxCharNum()`

- `SimpleLayoutContent get_avatarContainer()`

- `String get_slotId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingStationView : DataBinder`1, IProvider
{
	private SimpleLayoutContent _charLayout; // 0x20
	private TRoomViewModel m_viewModel; // 0x28
	private BuildingCharAvatarStationAdatper m_adapter; // 0x30
	private Boolean m_isInited; // 0x38
	public Action`2 onCharClicked; // 0x40
	private static DelegateBridge __Hotfix0_get_finalMaxCharNum; // 0x0
	private static DelegateBridge __Hotfix0_get_curMaxCharNum; // 0x8
	private static DelegateBridge __Hotfix0_get_stationedChars; // 0x10
	private static DelegateBridge __Hotfix0_Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.get_onCharClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_avatarContainer; // 0x20
	private static DelegateBridge __Hotfix0_get_slotId; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 finalMaxCharNum { get; }
	public Int32 curMaxCharNum { get; }
	public BuildingCharModel[] stationedChars { get; }
	private Action`2 Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.onCharClicked { get; }
	public SimpleLayoutContent avatarContainer { get; }
	public String slotId { get; }

	// RVA: 0x3d8afbc VA: 0x75963a2fbc
	public Int32 get_finalMaxCharNum() { }
	// RVA: 0x3d8b030 VA: 0x75963a3030
	public Int32 get_curMaxCharNum() { }
	// RVA: 0x3d8b0a4 VA: 0x75963a30a4
	public BuildingCharModel[] get_stationedChars() { }
	// RVA: 0x3d8b11c VA: 0x75963a311c
	private Action`2 Torappu.Building.UI.BuildingCharAvatarStationAdatper.IProvider.get_onCharClicked() { }
	// RVA: 0x3d8b184 VA: 0x75963a3184
	public SimpleLayoutContent get_avatarContainer() { }
	// RVA: 0x3d8b1ec VA: 0x75963a31ec
	public String get_slotId() { }
	// RVA: 0x3d8b280 VA: 0x75963a3280
	public override Void OnValueChanged(TRoomViewProperty property) { }
	// RVA: 0x3d8b37c VA: 0x75963a337c
	public Void .ctor() { }
}
```