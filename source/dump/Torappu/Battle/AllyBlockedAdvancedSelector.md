# AllyBlockedAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _onlyForToken`

- `Character m_character`


## Methods

- `Boolean ValidateEnemyTarget(Entity)`

- `Boolean ValidateAllyTarget(Entity)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AllyBlockedAdvancedSelector : BlockedBaseSelector
{
	private Boolean _onlyForToken; // 0xe8
	private List`1 m_tmpList; // 0xf0
	private Character m_character; // 0xf8
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x8
	private static DelegateBridge __Hotfix0_ValidateEnemyTarget; // 0x10
	private static DelegateBridge __Hotfix0_ValidateAllyTarget; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ba02f0 VA: 0x75941b82f0
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba0428 VA: 0x75941b8428
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba0c54 VA: 0x75941b8c54
	protected Boolean ValidateEnemyTarget(Entity target) { }
	// RVA: 0x1ba0d18 VA: 0x75941b8d18
	protected Boolean ValidateAllyTarget(Entity target) { }
	// RVA: 0x1ba0ddc VA: 0x75941b8ddc
	public Void .ctor() { }
	// RVA: 0x1ba0eb8 VA: 0x75941b8eb8
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba0ec0 VA: 0x75941b8ec0
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
}
```