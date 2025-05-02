# BlockedTargetWithIdSelector

**Namespace:** `Torappu.Battle`


## Methods

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedTargetWithIdSelector : BlockedSelector
{
	private List`1 _allowedId; // 0xa8
	private HashSet`1 m_allowedIdHashSet; // 0xb0
	private static DelegateBridge __Hotfix0_get_allowedId; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 allowedId { get; }

	// RVA: 0x1ba6ad4 VA: 0x75941bead4
	public List`1 get_allowedId() { }
	// RVA: 0x1ba6b3c VA: 0x75941beb3c
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba6c80 VA: 0x75941bec80
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba6d58 VA: 0x75941bed58
	public Void .ctor() { }
	// RVA: 0x1ba6e18 VA: 0x75941bee18
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba6e1c VA: 0x75941bee1c
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```