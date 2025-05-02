# BuildingTrainSelectIndexState

**Namespace:** `Torappu.Building.UI.TrainSelect`


## Fields

- `BuildingCharSelectMaskPlugin _maskPlugin`


## Properties

- `Boolean usePluginWorkingPanel`

- `Boolean usePluginDormLockPanel`


## Methods

- `Boolean get_usePluginWorkingPanel()`

- `Boolean get_usePluginDormLockPanel()`

- `RoomType GetCurrentRoomType()`

- `Boolean CheckIfCharValid(Int32)`

- `Void _OnJumpToCharSelect(CharSelectStateBean)`

- `Void <RegisterToDataListener>b__12_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.TrainSelect
public class BuildingTrainSelectIndexState : State, IBuildingCharSelectContext
{
	private BuildingCharSelectMaskPlugin _maskPlugin; // 0x50
	private List`1 m_tempListForExclusiveInstIds; // 0x58
	private static DelegateBridge __Hotfix0_get_usePluginWorkingPanel; // 0x0
	private static DelegateBridge __Hotfix0_get_usePluginDormLockPanel; // 0x8
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x10
	private static DelegateBridge __Hotfix0_GetCurrentRoomType; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToCharSelect; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean usePluginWorkingPanel { get; }
	public Boolean usePluginDormLockPanel { get; }

	// RVA: 0x3d753d8 VA: 0x759638d3d8
	public Boolean get_usePluginWorkingPanel() { }
	// RVA: 0x3d75440 VA: 0x759638d440
	public Boolean get_usePluginDormLockPanel() { }
	// RVA: 0x3d754a8 VA: 0x759638d4a8
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x3d75510 VA: 0x759638d510
	public RoomType GetCurrentRoomType() { }
	// RVA: 0x3d75578 VA: 0x759638d578
	public Boolean CheckIfCharValid(Int32 instId) { }
	// RVA: 0x3d755f4 VA: 0x759638d5f4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d75658 VA: 0x759638d658
	protected override Void OnEnter() { }
	// RVA: 0x3d756c4 VA: 0x759638d6c4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3d7583c VA: 0x759638d83c
	private Void _OnJumpToCharSelect(CharSelectStateBean selectBean) { }
	// RVA: 0x3d75d24 VA: 0x759638dd24
	public Void .ctor() { }
	// RVA: 0x3d75de8 VA: 0x759638dde8
	private Void <RegisterToDataListener>b__12_0(IStateBean stateBean) { }
	// RVA: 0x3d75e68 VA: 0x759638de68
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d75e70 VA: 0x759638de70
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```