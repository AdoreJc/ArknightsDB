# ExistCertainCharacterToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _charKey`

- `Boolean _chooseMyToken`

- `Boolean _inverse`

- `Int32 _minCnt`

- `Int32 m_minCnt`


## Methods

- `Void _OnUnitBornOrRallyPointReborn(Object)`

- `Boolean _CheckCondition()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ExistCertainCharacterToggleChecker : Checker
{
	private String _charKey; // 0x20
	private Boolean _chooseMyToken; // 0x28
	private Boolean _inverse; // 0x29
	private Int32 _minCnt; // 0x2c
	private Int32 m_minCnt; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_OnAttached; // 0x8
	private static DelegateBridge __Hotfix0_OnDetached; // 0x10
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x18
	private static DelegateBridge __Hotfix0__OnUnitBornOrRallyPointReborn; // 0x20
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x1e5b8cc VA: 0x75944738cc
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5b980 VA: 0x7594473980
	public override Void OnAttached() { }
	// RVA: 0x1e5baf4 VA: 0x7594473af4
	public override Void OnDetached() { }
	// RVA: 0x1e5bc68 VA: 0x7594473c68
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5c43c VA: 0x759447443c
	private Void _OnUnitBornOrRallyPointReborn(Object arg) { }
	// RVA: 0x1e5bcd0 VA: 0x7594473cd0
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5c538 VA: 0x7594474538
	public Void .ctor() { }
	// RVA: 0x1e5c5a4 VA: 0x75944745a4
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e5c5a8 VA: 0x75944745a8
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```