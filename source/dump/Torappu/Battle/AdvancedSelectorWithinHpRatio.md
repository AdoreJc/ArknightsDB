# AdvancedSelectorWithinHpRatio

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _filerMaxHp`

- `Boolean _maxHpExcludeEqual`

- `Single _maxHpRatio`

- `Boolean _filterMinHp`

- `Single _minHpRatio`


## Methods

- `Boolean _CheckHpRatio(Entity)`

- `Boolean <>xLuaBaseProxy_ValidateTarget(Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithinHpRatio : AdvancedSelector
{
	private Boolean _filerMaxHp; // 0xe8
	private Boolean _maxHpExcludeEqual; // 0xe9
	private Single _maxHpRatio; // 0xec
	private Boolean _filterMinHp; // 0xf0
	private Single _minHpRatio; // 0xf4
	private static DelegateBridge __Hotfix0_ValidateTarget; // 0x0
	private static DelegateBridge __Hotfix0__CheckHpRatio; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b9c8d0 VA: 0x75941b48d0
	protected override Boolean ValidateTarget(Entity target) { }
	// RVA: 0x1b9c974 VA: 0x75941b4974
	private Boolean _CheckHpRatio(Entity target) { }
	// RVA: 0x1b9cad4 VA: 0x75941b4ad4
	public Void .ctor() { }
	// RVA: 0x1b9cb50 VA: 0x75941b4b50
	private Boolean <>xLuaBaseProxy_ValidateTarget(Entity P0) { }
}
```