# HunterBulletTrigger

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _checkReloadFlag`

- `Int32 _reloadFlag`

- `Ability m_traitAbility`


## Properties

- `Ability traitAbility`


## Methods

- `Ability get_traitAbility()`

- `Boolean _CheckValid()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability)`

- `Boolean <>xLuaBaseProxy_Search(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class HunterBulletTrigger : SelectorTrigger
{
	private const String RELOAD_FLAG; // 0x0
	private List`1 _triggerValidType; // 0x50
	private Boolean _checkReloadFlag; // 0x58
	private Int32 _reloadFlag; // 0x5c
	private Ability m_traitAbility; // 0x60
	private static DelegateBridge __Hotfix0_get_traitAbility; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_Search; // 0x10
	private static DelegateBridge __Hotfix0__CheckValid; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Ability traitAbility { get; }

	// RVA: 0x1bd7990 VA: 0x75941ef990
	private Ability get_traitAbility() { }
	// RVA: 0x1bd7d28 VA: 0x75941efd28
	public override Void Reset(Entity owner, Ability ability) { }
	// RVA: 0x1bd7dc4 VA: 0x75941efdc4
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd7e64 VA: 0x75941efe64
	private Boolean _CheckValid() { }
	// RVA: 0x1bd8160 VA: 0x75941f0160
	public Void .ctor() { }
	// RVA: 0x1bd81cc VA: 0x75941f01cc
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1) { }
	// RVA: 0x1bd81d0 VA: 0x75941f01d0
	private Boolean <>xLuaBaseProxy_Search(Boolean P0) { }
}
```