# PassiveAttachmentAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `FamilyGroupMask _targetFamilyMask`

- `TargetValidator _targetValidator`

- `String _probKey`

- `AbilityAttachment m_attachment`


## Methods

- `Boolean <>xLuaBaseProxy_get_isAffecting()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PassiveAttachmentAbility : PassiveBuffAbility
{
	private BuffData[] _additiveActiveBuffs; // 0x110
	private FamilyGroupMask _targetFamilyMask; // 0x118
	private TargetValidator _targetValidator; // 0x120
	private String _probKey; // 0x128
	private AbilityAttachment m_attachment; // 0x130
	private static DelegateBridge __Hotfix0_get_isAffecting; // 0x0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x8
	private static DelegateBridge __Hotfix0_DoSetData; // 0x10
	private static DelegateBridge __Hotfix0_DoAttach; // 0x18
	private static DelegateBridge __Hotfix0_DoDetach; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Boolean isAffecting { get; }

	// RVA: 0x1e54788 VA: 0x759446c788
	public override Boolean get_isAffecting() { }
	// RVA: 0x1e547f4 VA: 0x759446c7f4
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1e548b8 VA: 0x759446c8b8
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e549e0 VA: 0x759446c9e0
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e54b0c VA: 0x759446cb0c
	protected override Void DoDetach() { }
	// RVA: 0x1e54be8 VA: 0x759446cbe8
	public Void .ctor() { }
	// RVA: 0x1e54c94 VA: 0x759446cc94
	private Boolean <>xLuaBaseProxy_get_isAffecting() { }
	// RVA: 0x1e54c9c VA: 0x759446cc9c
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
	// RVA: 0x1e54ca4 VA: 0x759446cca4
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e54ccc VA: 0x759446cccc
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e54cd4 VA: 0x759446ccd4
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```