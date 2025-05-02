# ProfessionCntToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `ProfessionCategory _professionMask`

- `Int32 _minCount`

- `Boolean _forceToggleFlag`

- `Boolean _checkMaxSameProfessionCount`

- `Boolean _checkMaxDifferentProfessionCount`

- `Int32 m_conditionCount`


## Methods

- `Boolean _CheckCondition()`

- `Int32 _CheckProfessionCount()`

- `Int32 _CheckMaxSameProfessionCount()`

- `Int32 _CheckMaxDifferentProfessionCount()`

- `Void _OnCharacterChanged(Object)`

- `Boolean _CheckProfession(Unit)`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ProfessionCntToggleChecker : Checker
{
	private ProfessionCategory _professionMask; // 0x20
	private Int32 _minCount; // 0x24
	private Boolean _forceToggleFlag; // 0x28
	private Boolean _checkMaxSameProfessionCount; // 0x29
	private Boolean _checkMaxDifferentProfessionCount; // 0x2a
	private Int32 m_conditionCount; // 0x2c
	private ListDict`2 m_professionCount; // 0x30
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge __Hotfix0_OnAttached; // 0x10
	private static DelegateBridge __Hotfix0_OnDetached; // 0x18
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x20
	private static DelegateBridge __Hotfix0__CheckProfessionCount; // 0x28
	private static DelegateBridge __Hotfix0__CheckMaxSameProfessionCount; // 0x30
	private static DelegateBridge __Hotfix0__CheckMaxDifferentProfessionCount; // 0x38
	private static DelegateBridge __Hotfix0__OnCharacterChanged; // 0x40
	private static DelegateBridge __Hotfix0__CheckProfession; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1e5d888 VA: 0x7594475888
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5d990 VA: 0x7594475990
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5da44 VA: 0x7594475a44
	public override Void OnAttached() { }
	// RVA: 0x1e5dc14 VA: 0x7594475c14
	public override Void OnDetached() { }
	// RVA: 0x1e5d8f0 VA: 0x75944758f0
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5e414 VA: 0x7594476414
	private Int32 _CheckProfessionCount() { }
	// RVA: 0x1e5dde4 VA: 0x7594475de4
	private Int32 _CheckMaxSameProfessionCount() { }
	// RVA: 0x1e5e170 VA: 0x7594476170
	private Int32 _CheckMaxDifferentProfessionCount() { }
	// RVA: 0x1e5e6dc VA: 0x75944766dc
	private Void _OnCharacterChanged(Object arg) { }
	// RVA: 0x1e5e5a0 VA: 0x75944765a0
	private Boolean _CheckProfession(Unit target) { }
	// RVA: 0x1e5e7f0 VA: 0x75944767f0
	public Void .ctor() { }
	// RVA: 0x1e5e8b0 VA: 0x75944768b0
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1e5e8b4 VA: 0x75944768b4
	private Void <>xLuaBaseProxy_OnDetached() { }
}
```