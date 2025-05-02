# LevelBranchTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _isLoop`

- `String _branchId`

- `String m_branchId`


## Methods

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LevelBranchTrigger : TargetTrigger
{
	private Boolean _isLoop; // 0x20
	private String _branchId; // 0x28
	private String m_branchId; // 0x30
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge __Hotfix0_Search; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd8ad4 VA: 0x75941f0ad4
	public override Entity get_target() { }
	// RVA: 0x1bd8b38 VA: 0x75941f0b38
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd8c3c VA: 0x75941f0c3c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bd8d00 VA: 0x75941f0d00
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd8d84 VA: 0x75941f0d84
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd8e08 VA: 0x75941f0e08
	public Void .ctor() { }
	// RVA: 0x1bd8e74 VA: 0x75941f0e74
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
	// RVA: 0x1bd8e78 VA: 0x75941f0e78
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
}
```