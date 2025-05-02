# BlockedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _maxTargetNum`

- `TargetOptions m_targetOptions`

- `Enemy m_enemy`

- `Character <character>k__BackingField`


## Properties

- `Character character`

- `Int32 maxTargetNum`


## Methods

- `Character get_character()`

- `Void set_character(Character)`

- `Int32 get_maxTargetNum()`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BlockedSelector : TargetSelector
{
	private Int32 _maxTargetNum; // 0x30
	private TargetOptions m_targetOptions; // 0x38
	private Enemy m_enemy; // 0x98
	private Character <character>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_character; // 0x0
	private static DelegateBridge __Hotfix0_set_character; // 0x8
	private static DelegateBridge __Hotfix0_get_ignoreTargetFree; // 0x10
	private static DelegateBridge __Hotfix0_get_ignoreAllyTargetFree; // 0x18
	private static DelegateBridge __Hotfix0_get_ignoreHealFree; // 0x20
	private static DelegateBridge __Hotfix0_get_onlyIgnoreSomeOfTargetFreeCase; // 0x28
	private static DelegateBridge __Hotfix0_get_abnormalFlag; // 0x30
	private static DelegateBridge __Hotfix0_get_abnormalCombo; // 0x38
	private static DelegateBridge __Hotfix0_get_maxTargetNum; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x50
	private static DelegateBridge __Hotfix0_FindTiles; // 0x58
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x60
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	protected Character character { get; set; }
	protected virtual Boolean ignoreTargetFree { get; }
	protected virtual Boolean ignoreAllyTargetFree { get; }
	protected virtual Boolean ignoreHealFree { get; }
	protected virtual Boolean onlyIgnoreSomeOfTargetFreeCase { get; }
	protected virtual AbnormalFlag abnormalFlag { get; }
	protected virtual AbnormalCombo abnormalCombo { get; }
	protected Int32 maxTargetNum { get; }

	// RVA: 0x1ba53d4 VA: 0x75941bd3d4
	protected Character get_character() { }
	// RVA: 0x1ba543c VA: 0x75941bd43c
	private Void set_character(Character value) { }
	// RVA: 0x1ba54c0 VA: 0x75941bd4c0
	protected virtual Boolean get_ignoreTargetFree() { }
	// RVA: 0x1ba5528 VA: 0x75941bd528
	protected virtual Boolean get_ignoreAllyTargetFree() { }
	// RVA: 0x1ba558c VA: 0x75941bd58c
	protected virtual Boolean get_ignoreHealFree() { }
	// RVA: 0x1ba55f0 VA: 0x75941bd5f0
	protected virtual Boolean get_onlyIgnoreSomeOfTargetFreeCase() { }
	// RVA: 0x1ba5654 VA: 0x75941bd654
	protected virtual AbnormalFlag get_abnormalFlag() { }
	// RVA: 0x1ba56bc VA: 0x75941bd6bc
	protected virtual AbnormalCombo get_abnormalCombo() { }
	// RVA: 0x1ba5724 VA: 0x75941bd724
	protected Int32 get_maxTargetNum() { }
	// RVA: 0x1ba5798 VA: 0x75941bd798
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1ba5ae0 VA: 0x75941bdae0
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 pos) { }
	// RVA: 0x1ba5ef0 VA: 0x75941bdef0
	public override List`1 FindTiles(Vector2 pos) { }
	// RVA: 0x1ba5f70 VA: 0x75941bdf70
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1ba6228 VA: 0x75941be228
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1ba62f4 VA: 0x75941be2f4
	public Void .ctor() { }
	// RVA: 0x1ba636c VA: 0x75941be36c
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1ba6374 VA: 0x75941be374
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```