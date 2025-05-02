# BuildingPrivateSelectIndexState

**Namespace:** `Torappu.Building.UI`


## Fields

- `BuildingPrivateSelectMaskPlugin _maskPlugin`

- `Param m_param`


## Properties

- `Boolean usePluginWorkingPanel`

- `Boolean usePluginDormLockPanel`


## Methods

- `Void _OnJumpToCharSelect(CharSelectStateBean)`

- `Boolean get_usePluginWorkingPanel()`

- `Boolean get_usePluginDormLockPanel()`

- `RoomType GetCurrentRoomType()`

- `Boolean CheckIfCharValid(Int32)`

- `Void <RegisterToDataListener>b__6_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingPrivateSelectIndexState : State, IBuildingCharSelectContext
{
	private BuildingPrivateSelectMaskPlugin _maskPlugin; // 0x50
	private List`1 m_tempListForExclusiveInstIds; // 0x58
	private Param m_param; // 0x60
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToCharSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_usePluginWorkingPanel; // 0x20
	private static DelegateBridge __Hotfix0_get_usePluginDormLockPanel; // 0x28
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x30
	private static DelegateBridge __Hotfix0_GetCurrentRoomType; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfCharValid; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean usePluginWorkingPanel { get; }
	public Boolean usePluginDormLockPanel { get; }

	// RVA: 0x3d544f4 VA: 0x759636c4f4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d54558 VA: 0x759636c558
	protected override Void OnEnter() { }
	// RVA: 0x3d5462c VA: 0x759636c62c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3d547a4 VA: 0x759636c7a4
	private Void _OnJumpToCharSelect(CharSelectStateBean selectBean) { }
	// RVA: 0x3d54ab0 VA: 0x759636cab0
	public Boolean get_usePluginWorkingPanel() { }
	// RVA: 0x3d54b14 VA: 0x759636cb14
	public Boolean get_usePluginDormLockPanel() { }
	// RVA: 0x3d54b78 VA: 0x759636cb78
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x3d54be0 VA: 0x759636cbe0
	public RoomType GetCurrentRoomType() { }
	// RVA: 0x3d54c48 VA: 0x759636cc48
	public Boolean CheckIfCharValid(Int32 instId) { }
	// RVA: 0x3d54cc4 VA: 0x759636ccc4
	public Void .ctor() { }
	// RVA: 0x3d54d88 VA: 0x759636cd88
	private Void <RegisterToDataListener>b__6_0(IStateBean stateBean) { }
	// RVA: 0x3d54e08 VA: 0x759636ce08
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d54e10 VA: 0x759636ce10
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```