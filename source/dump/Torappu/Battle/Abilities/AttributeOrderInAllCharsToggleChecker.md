# AttributeOrderInAllCharsToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `TargetOptions _targetOptions`

- `Int32 _num`

- `Boolean _isAsc`

- `Single _tickInterval`

- `CompareTargetType _targetType`

- `AttributeType _attributeType`

- `PeriodicTimer m_timer`


## Properties

- `Boolean compareAttribute`


## Methods

- `Boolean get_compareAttribute()`

- `Boolean _CheckToggled()`

- `FP _GetValue(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AttributeOrderInAllCharsToggleChecker : Checker
{
	private TargetOptions _targetOptions; // 0x20
	private Int32 _num; // 0x80
	private Boolean _isAsc; // 0x84
	private Single _tickInterval; // 0x88
	private CompareTargetType _targetType; // 0x8c
	private AttributeType _attributeType; // 0x90
	private PeriodicTimer m_timer; // 0x98
	private static DelegateBridge __Hotfix0_get_compareAttribute; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0__CheckToggled; // 0x20
	private static DelegateBridge __Hotfix0__GetValue; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean compareAttribute { get; }

	// RVA: 0x1e595ec VA: 0x75944715ec
	private Boolean get_compareAttribute() { }
	// RVA: 0x1e5965c VA: 0x759447165c
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e597a8 VA: 0x75944717a8
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e59d0c VA: 0x7594471d0c
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e59810 VA: 0x7594471810
	private Boolean _CheckToggled() { }
	// RVA: 0x1e59de4 VA: 0x7594471de4
	private FP _GetValue(Entity entity) { }
	// RVA: 0x1e59f10 VA: 0x7594471f10
	public Void .ctor() { }
	// RVA: 0x1e59f84 VA: 0x7594471f84
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```