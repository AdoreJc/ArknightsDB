# EddSkillSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Tile m_endTile`


## Properties

- `Tile endTile`


## Methods

- `Tile get_endTile()`

- `Void _FetchEndTile()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EddSkillSelector : AdvancedSelector
{
	private Tile m_endTile; // 0xe8
	private List`1 m_grids; // 0xf0
	private static DelegateBridge __Hotfix0_get_endTile; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x10
	private static DelegateBridge __Hotfix0__FetchEndTile; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Tile endTile { get; }

	// RVA: 0x1bbef78 VA: 0x75941d6f78
	public Tile get_endTile() { }
	// RVA: 0x1bbf4d8 VA: 0x75941d74d8
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1bbf5b8 VA: 0x75941d75b8
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbf024 VA: 0x75941d7024
	private Void _FetchEndTile() { }
	// RVA: 0x1bbf710 VA: 0x75941d7710
	public Void .ctor() { }
	// RVA: 0x1bbf7d4 VA: 0x75941d77d4
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1bbf7dc VA: 0x75941d77dc
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```