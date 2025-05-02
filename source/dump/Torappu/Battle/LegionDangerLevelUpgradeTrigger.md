# LegionDangerLevelUpgradeTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 m_curLevel`

- `LegionGameMode m_gameMode`


## Methods

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LegionDangerLevelUpgradeTrigger : TargetTrigger
{
	private Int32 m_curLevel; // 0x20
	private LegionGameMode m_gameMode; // 0x28
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x10
	private static DelegateBridge __Hotfix0_Search; // 0x18
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }

	// RVA: 0x1bd81d8 VA: 0x75941f01d8
	public override Entity get_target() { }
	// RVA: 0x1bd823c VA: 0x75941f023c
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bd83b4 VA: 0x75941f03b4
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd841c VA: 0x75941f041c
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd84c0 VA: 0x75941f04c0
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd853c VA: 0x75941f053c
	public Void .ctor() { }
	// RVA: 0x1bd85b0 VA: 0x75941f05b0
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1bd85b4 VA: 0x75941f05b4
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
}
```