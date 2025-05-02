# AdvancedSelectorWithValidatorFilter

**Namespace:** `Torappu.Battle`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithValidatorFilter : AdvancedSelector
{
	public List`1 _validatorFilterSettings; // 0xe8
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1bbdba8 VA: 0x75941d5ba8
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bbde9c VA: 0x75941d5e9c
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1bbe0c8 VA: 0x75941d60c8
	public Void .ctor() { }
	// RVA: 0x1bbe18c VA: 0x75941d618c
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bbe194 VA: 0x75941d6194
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```