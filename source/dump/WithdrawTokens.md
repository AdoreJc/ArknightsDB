# WithdrawTokens

**Namespace:** ` `


## Fields

- `Boolean _switchToDeadState`

- `Boolean _force`

- `Boolean _checkContainsBuff`

- `String _buffKey`

- `Boolean _needLog`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class WithdrawTokens : ActionNode
{
	private Boolean _switchToDeadState; // 0x10
	private Boolean _force; // 0x11
	private Boolean _checkContainsBuff; // 0x12
	private String _buffKey; // 0x18
	private Boolean _needLog; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe8ce0 VA: 0x7594600ce0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe8d48 VA: 0x7594600d48
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe905c VA: 0x759460105c
	public Void .ctor() { }
}
```