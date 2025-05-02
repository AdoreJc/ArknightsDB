# RacingItemTargetSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Single _maxDegree`

- `FP m_maxDegree`


## Methods

- `Boolean _ValidateTargetInArc(Entity)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RacingItemTargetSelector : AdvancedSelector
{
	private Single _maxDegree; // 0xe8
	private FP m_maxDegree; // 0xf0
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x8
	private static DelegateBridge __Hotfix0__ValidateTargetInArc; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x40b9cac VA: 0x75966d1cac
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x40b9db0 VA: 0x75966d1db0
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x40b9e9c VA: 0x75966d1e9c
	private Boolean _ValidateTargetInArc(Entity target) { }
	// RVA: 0x40ba080 VA: 0x75966d2080
	public Void .ctor() { }
	// RVA: 0x40ba0f0 VA: 0x75966d20f0
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x40ba0f8 VA: 0x75966d20f8
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```