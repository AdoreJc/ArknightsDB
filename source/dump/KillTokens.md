# KillTokens

**Namespace:** ` `


## Fields

- `Boolean _checkContainsBuff`

- `String _buffKey`


## Properties

- `Boolean checkContainsBuff`


## Methods

- `Boolean get_checkContainsBuff()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class KillTokens : ActionNode
{
	private Boolean _checkContainsBuff; // 0x10
	private String _buffKey; // 0x18
	private static DelegateBridge __Hotfix0_get_checkContainsBuff; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean checkContainsBuff { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1fe8898 VA: 0x7594600898
	public Boolean get_checkContainsBuff() { }
	// RVA: 0x1fe8900 VA: 0x7594600900
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe8968 VA: 0x7594600968
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe8c38 VA: 0x7594600c38
	public Void .ctor() { }
}
```