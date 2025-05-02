# CreateBuffToCharacterInSpecifiedArea

**Namespace:** ` `


## Fields

- `Boolean _specifyByGridColumn`

- `BuffData _buffData`

- `Boolean _isDerivedBuff`

- `Boolean _ignoreTrap`

- `Boolean _ignoreToken`

- `Boolean _isExclude`


## Methods

- `Void GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CreateBuffToCharacterInSpecifiedArea : ActionNode, IBuffSource
{
	private Boolean _specifyByGridColumn; // 0x10
	private BuffData _buffData; // 0x18
	private Boolean _isDerivedBuff; // 0x20
	private Boolean _ignoreTrap; // 0x21
	private Boolean _ignoreToken; // 0x22
	private Boolean _isExclude; // 0x23
	private List`1 m_tileList; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0531c VA: 0x759451d31c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f05384 VA: 0x759451d384
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f057d8 VA: 0x759451d7d8
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1f058e0 VA: 0x759451d8e0
	public Void .ctor() { }
}
```