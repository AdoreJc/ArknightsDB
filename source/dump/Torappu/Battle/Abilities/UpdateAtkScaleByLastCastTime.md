# UpdateAtkScaleByLastCastTime

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _createNewNodeEachTime`

- `FP m_minDeltaTime`

- `FP m_maxDeltaTime`

- `FP m_minAtkScale`

- `FP m_maxAtkScale`

- `FP m_accumCastTime`


## Methods

- `FP _GetAtkScale(FP)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UpdateAtkScaleByLastCastTime : Behaviour
{
	private Boolean _createNewNodeEachTime; // 0x20
	private FP m_minDeltaTime; // 0x28
	private FP m_maxDeltaTime; // 0x30
	private FP m_minAtkScale; // 0x38
	private FP m_maxAtkScale; // 0x40
	private FP m_accumCastTime; // 0x48
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__GetAtkScale; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ed32a4 VA: 0x75944eb2a4
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1ed34a8 VA: 0x75944eb4a8
	public override Void OnCastStart() { }
	// RVA: 0x1ed3708 VA: 0x75944eb708
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ed360c VA: 0x75944eb60c
	private FP _GetAtkScale(FP deltaTime) { }
	// RVA: 0x1ed37cc VA: 0x75944eb7cc
	public Void .ctor() { }
	// RVA: 0x1ed3878 VA: 0x75944eb878
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1ed3880 VA: 0x75944eb880
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ed3888 VA: 0x75944eb888
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```