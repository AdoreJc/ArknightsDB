# SelectorTriggerWithCertainCondition

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _checkContainBuffs`

- `Boolean _isAnd`

- `Boolean _checkHasSp`


## Properties

- `Boolean checkContainBuffs`


## Methods

- `Boolean get_checkContainBuffs()`

- `Boolean <>xLuaBaseProxy_Search(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SelectorTriggerWithCertainCondition : SelectorTrigger
{
	private Boolean _checkContainBuffs; // 0x50
	private Boolean _isAnd; // 0x51
	private String[] _buffKeys; // 0x58
	private Boolean _checkHasSp; // 0x60
	private static DelegateBridge __Hotfix0_get_checkContainBuffs; // 0x0
	private static DelegateBridge __Hotfix0_Search; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean checkContainBuffs { get; }

	// RVA: 0x1bd9954 VA: 0x75941f1954
	public Boolean get_checkContainBuffs() { }
	// RVA: 0x1bd99bc VA: 0x75941f19bc
	public override Boolean Search(Boolean force) { }
	// RVA: 0x1bd9b54 VA: 0x75941f1b54
	public Void .ctor() { }
	// RVA: 0x1bd9bc8 VA: 0x75941f1bc8
	private Boolean <>xLuaBaseProxy_Search(Boolean P0) { }
}
```