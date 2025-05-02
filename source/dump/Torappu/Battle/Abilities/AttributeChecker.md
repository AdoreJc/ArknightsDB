# AttributeChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `AttributeType _attributeType`

- `CompareType _condType`

- `Single _condition`

- `Single m_condition`

- `Boolean m_hasToggleChanged`


## Methods

- `Boolean _CheckToggled()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AttributeChecker : Checker
{
	private AttributeType _attributeType; // 0x20
	private CompareType _condType; // 0x24
	private Single _condition; // 0x28
	private Single m_condition; // 0x2c
	private Boolean m_hasToggleChanged; // 0x30
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__CheckToggled; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e59284 VA: 0x7594471284
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e59434 VA: 0x7594471434
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e594e8 VA: 0x75944714e8
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e592ec VA: 0x75944712ec
	private Boolean _CheckToggled() { }
	// RVA: 0x1e59570 VA: 0x7594471570
	public Void .ctor() { }
	// RVA: 0x1e595e8 VA: 0x75944715e8
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```