# AdvancedSelectorWithinHpRatioInBb

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _filerMaxHp`

- `Single _maxHpRatio`

- `Boolean _loadMaxHpRatioFromBb`

- `String _maxHpBlackboardKey`

- `Boolean _maxHpExcludeEqual`

- `Boolean _filterMinHp`

- `Single _minHpRatio`

- `Boolean _loadMinHpRatioFromBb`

- `String _minHpBlackboardKey`

- `Boolean _minHpExcludeEqual`

- `FP m_minHpRatio`

- `FP m_maxHpRatio`


## Methods

- `Void _Init(Blackboard)`

- `Boolean _CheckHpRatio(Entity)`

- `Void <>xLuaBaseProxy_SetData(Blackboard)`

- `Void <>xLuaBaseProxy_Reset(Entity, Ability, Func`2)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithinHpRatioInBb : AdvancedSelector
{
	private Boolean _filerMaxHp; // 0xe8
	private Single _maxHpRatio; // 0xec
	private Boolean _loadMaxHpRatioFromBb; // 0xf0
	private String _maxHpBlackboardKey; // 0xf8
	private Boolean _maxHpExcludeEqual; // 0x100
	private Boolean _filterMinHp; // 0x101
	private Single _minHpRatio; // 0x104
	private Boolean _loadMinHpRatioFromBb; // 0x108
	private String _minHpBlackboardKey; // 0x110
	private Boolean _minHpExcludeEqual; // 0x118
	private FP m_minHpRatio; // 0x120
	private FP m_maxHpRatio; // 0x128
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x10
	private static DelegateBridge __Hotfix0__Init; // 0x18
	private static DelegateBridge __Hotfix0__CheckHpRatio; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b9cb54 VA: 0x75941b4b54
	public override Void SetData(Blackboard blackboard) { }
	// RVA: 0x1b9cd68 VA: 0x75941b4d68
	public override Void Reset(Entity owner, Ability ability, Func`2 validator) { }
	// RVA: 0x1b9ce68 VA: 0x75941b4e68
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1b9cbe0 VA: 0x75941b4be0
	private Void _Init(Blackboard blackboard) { }
	// RVA: 0x1b9cf0c VA: 0x75941b4f0c
	private Boolean _CheckHpRatio(Entity target) { }
	// RVA: 0x1b9d064 VA: 0x75941b5064
	public Void .ctor() { }
	// RVA: 0x1b9d134 VA: 0x75941b5134
	private Void <>xLuaBaseProxy_SetData(Blackboard P0) { }
	// RVA: 0x1b9d138 VA: 0x75941b5138
	private Void <>xLuaBaseProxy_Reset(Entity P0, Ability P1, Func`2 P2) { }
	// RVA: 0x1b9d13c VA: 0x75941b513c
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```