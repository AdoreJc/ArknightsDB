# SkillSubTalents

**Namespace:** `Torappu.Battle.Skills`


## Methods

- `Void _AssignSubTalents(Dictionary`2)`

- `Void _ActivateSubTalent()`

- `Void _InactivateSubTalent()`

- `Void Awake()`

- `Void <>xLuaBaseProxy_PostprocessData(Dictionary`2)`

- `Void <>xLuaBaseProxy_OnSkillStart()`

- `Void <>xLuaBaseProxy_OnSkillEnd()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Skills
public class SkillSubTalents : Behaviour
{
	private ConstrainedTalent[] m_talents; // 0x20
	private static DelegateBridge __Hotfix0_PostprocessData; // 0x0
	private static DelegateBridge __Hotfix0_OnSkillStart; // 0x8
	private static DelegateBridge __Hotfix0_OnSkillEnd; // 0x10
	private static DelegateBridge __Hotfix0__AssignSubTalents; // 0x18
	private static DelegateBridge __Hotfix0__ActivateSubTalent; // 0x20
	private static DelegateBridge __Hotfix0__InactivateSubTalent; // 0x28
	private static DelegateBridge __Hotfix0_Awake; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x1d34c1c VA: 0x759434cc1c
	public override Void PostprocessData(Dictionary`2 talentMap) { }
	// RVA: 0x1d34fac VA: 0x759434cfac
	public override Void OnSkillStart() { }
	// RVA: 0x1d351bc VA: 0x759434d1bc
	public override Void OnSkillEnd() { }
	// RVA: 0x1d34cac VA: 0x759434ccac
	private Void _AssignSubTalents(Dictionary`2 talentMap) { }
	// RVA: 0x1d35020 VA: 0x759434d020
	private Void _ActivateSubTalent() { }
	// RVA: 0x1d35230 VA: 0x759434d230
	private Void _InactivateSubTalent() { }
	// RVA: 0x1d35368 VA: 0x759434d368
	private Void Awake() { }
	// RVA: 0x1d353fc VA: 0x759434d3fc
	public Void .ctor() { }
	// RVA: 0x1d3546c VA: 0x759434d46c
	private Void <>xLuaBaseProxy_PostprocessData(Dictionary`2 P0) { }
	// RVA: 0x1d35474 VA: 0x759434d474
	private Void <>xLuaBaseProxy_OnSkillStart() { }
	// RVA: 0x1d3547c VA: 0x759434d47c
	private Void <>xLuaBaseProxy_OnSkillEnd() { }
}
```