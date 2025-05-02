# SkillSyncedTalent

**Namespace:** `Torappu.Battle`


## Methods

- `Void _OnSkillStart(Object)`

- `Void _OnSkillFinish(Object)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SkillSyncedTalent : Talent
{
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge __Hotfix0__OnSkillStart; // 0x10
	private static DelegateBridge __Hotfix0__OnSkillFinish; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1b7ffa8 VA: 0x7594197fa8
	protected override Void DoAttach() { }
	// RVA: 0x1b80110 VA: 0x7594198110
	protected override Void DoDetach() { }
	// RVA: 0x1b802c8 VA: 0x75941982c8
	private Void _OnSkillStart(Object arg) { }
	// RVA: 0x1b80368 VA: 0x7594198368
	private Void _OnSkillFinish(Object arg) { }
	// RVA: 0x1b803f4 VA: 0x75941983f4
	public Void .ctor() { }
	// RVA: 0x1b80460 VA: 0x7594198460
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b80464 VA: 0x7594198464
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```