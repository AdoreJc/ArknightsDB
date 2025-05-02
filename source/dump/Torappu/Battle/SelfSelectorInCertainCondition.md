# SelfSelectorInCertainCondition

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _checkHpRatioCondition`

- `Single _maxRatio`

- `Boolean _checkNotContainBuffs`

- `Boolean _checkContainBuffs`

- `FP m_maxRatio`


## Methods

- `Boolean _CheckSelfMeetCertainConditions()`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SelfSelectorInCertainCondition : SelfSelector
{
	private Boolean _checkHpRatioCondition; // 0x30
	private Single _maxRatio; // 0x34
	private Boolean _checkNotContainBuffs; // 0x38
	private Boolean _checkContainBuffs; // 0x39
	private String[] _buffKeys; // 0x40
	private FP m_maxRatio; // 0x48
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0__CheckSelfMeetCertainConditions; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1bbab10 VA: 0x75941d2b10
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1bbae78 VA: 0x75941d2e78
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1bbac50 VA: 0x75941d2c50
	private Boolean _CheckSelfMeetCertainConditions() { }
	// RVA: 0x1bbaf94 VA: 0x75941d2f94
	public Void .ctor() { }
	// RVA: 0x1bbb000 VA: 0x75941d3000
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1bbb004 VA: 0x75941d3004
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
}
```