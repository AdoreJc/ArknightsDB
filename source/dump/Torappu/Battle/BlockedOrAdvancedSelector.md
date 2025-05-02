# BlockedOrAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _limitedMaxTargetNumToBlockedCnt`

- `Boolean _allowZeroBlockCntLimit`

- `Character <character>k__BackingField`


## Properties

- `Character character`

- `Boolean limitedMaxTargetNumToBlockedCnt`

- `Boolean allowZeroBlockCntLimit`


## Methods

- `Character get_character()`

- `Void set_character(Character)`

- `Boolean get_limitedMaxTargetNumToBlockedCnt()`

- `Boolean get_allowZeroBlockCntLimit()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedOrAdvancedSelector : BlockedBaseSelector
{
	private Boolean _limitedMaxTargetNumToBlockedCnt; // 0xe8
	private Boolean _allowZeroBlockCntLimit; // 0xe9
	protected List`1 m_tmpList; // 0xf0
	private Character <character>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_get_limitedMaxTargetNumToBlockedCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_allowZeroBlockCntLimit; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x28
	private static DelegateBridge __Hotfix0_DoBaseFindTargets_DISPOSE; // 0x30
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	protected Character character { get; set; }
	protected Boolean limitedMaxTargetNumToBlockedCnt { get; }
	protected Boolean allowZeroBlockCntLimit { get; }

	// RVA: 0x1ba1874 VA: 0x75941b9874
	protected Character get_character() { }
	// RVA: 0x1ba39d0 VA: 0x75941bb9d0
	private Void set_character(Character value) { }
	// RVA: 0x1ba1aac VA: 0x75941b9aac
	protected Boolean get_limitedMaxTargetNumToBlockedCnt() { }
	// RVA: 0x1ba1b14 VA: 0x75941b9b14
	protected Boolean get_allowZeroBlockCntLimit() { }
	// RVA: 0x1ba3a54 VA: 0x75941bba54
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba1f60 VA: 0x75941b9f60
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba1a1c VA: 0x75941b9a1c
	protected ReusableList`1 DoBaseFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba3b50 VA: 0x75941bbb50
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba1e78 VA: 0x75941b9e78
	public Void .ctor() { }
	// RVA: 0x1ba3c0c VA: 0x75941bbc0c
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba3c14 VA: 0x75941bbc14
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0) { }
	// RVA: 0x1ba3c1c VA: 0x75941bbc1c
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```