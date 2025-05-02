# AuraAttachmentAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `FamilyGroupMask _targetFamilyMask`

- `TargetValidator _attachTargetValidator`

- `AbilityAttachment m_attachment`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Boolean <>xLuaBaseProxy_DealTargetTouched(Entity, TargetMeta)`

- `Void <>xLuaBaseProxy_DealTargetLeft(Entity, TargetMeta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class AuraAttachmentAbility : AuraAbility
{
	private BuffData[] _additiveActiveBuffs; // 0x178
	private FamilyGroupMask _targetFamilyMask; // 0x180
	private TargetValidator _attachTargetValidator; // 0x188
	private AbilityAttachment m_attachment; // 0x190
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x8
	private static DelegateBridge __Hotfix0_DealTargetTouched; // 0x10
	private static DelegateBridge __Hotfix0_DealTargetLeft; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1e3fe24 VA: 0x7594457e24
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e3ff54 VA: 0x7594457f54
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e40024 VA: 0x7594458024
	protected override Boolean DealTargetTouched(Entity target, TargetMeta meta) { }
	// RVA: 0x1e400e0 VA: 0x75944580e0
	protected override Void DealTargetLeft(Entity target, TargetMeta meta) { }
	// RVA: 0x1e40184 VA: 0x7594458184
	public Void .ctor() { }
	// RVA: 0x1e40230 VA: 0x7594458230
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e40254 VA: 0x7594458254
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e40258 VA: 0x7594458258
	private Boolean <>xLuaBaseProxy_DealTargetTouched(Entity P0, TargetMeta P1) { }
	// RVA: 0x1e4025c VA: 0x759445825c
	private Void <>xLuaBaseProxy_DealTargetLeft(Entity P0, TargetMeta P1) { }
}
```