# GroupTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `CheckType _checkType`

- `Boolean _resetTriggers`

- `Boolean _isOverrideSelector`

- `TargetSelector _overrideSelector`

- `Boolean _useRealCheckTargetIn`


## Methods

- `Boolean <>xLuaBaseProxy_get_isReadyToTrig()`

- `TargetSelector <>xLuaBaseProxy_get_selector()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class GroupTrigger : TargetTrigger
{
	private TargetTrigger[] _triggers; // 0x20
	private CheckType _checkType; // 0x28
	private Boolean _resetTriggers; // 0x2c
	private Boolean _isOverrideSelector; // 0x2d
	private TargetSelector _overrideSelector; // 0x30
	private Boolean _useRealCheckTargetIn; // 0x38
	private ObjectPtr`1 m_lastTarget; // 0x40
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_get_isReadyToTrig; // 0x8
	private static DelegateBridge __Hotfix0_get_selector; // 0x10
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_SetData; // 0x28
	private static DelegateBridge __Hotfix0_Search; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Entity target { get; }
	public override Boolean isReadyToTrig { get; }
	public override TargetSelector selector { get; }

	// RVA: 0x1bd7088 VA: 0x75941ef088
	public override Entity get_target() { }
	// RVA: 0x1bd7108 VA: 0x75941ef108
	public override Boolean get_isReadyToTrig() { }
	// RVA: 0x1bd7184 VA: 0x75941ef184
	public override TargetSelector get_selector() { }
	// RVA: 0x1bd72a4 VA: 0x75941ef2a4
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1bd7480 VA: 0x75941ef480
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd75a8 VA: 0x75941ef5a8
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bd76f8 VA: 0x75941ef6f8
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd78d0 VA: 0x75941ef8d0
	public Void .ctor() { }
	// RVA: 0x1bd7980 VA: 0x75941ef980
	private Boolean <>xLuaBaseProxy_get_isReadyToTrig() { }
	// RVA: 0x1bd7984 VA: 0x75941ef984
	private TargetSelector <>xLuaBaseProxy_get_selector() { }
	// RVA: 0x1bd7988 VA: 0x75941ef988
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
	// RVA: 0x1bd798c VA: 0x75941ef98c
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
}
```