# Withdraw

**Namespace:** ` `


## Fields

- `Boolean _withdrawSource`

- `Boolean _switchToDeadState`

- `Boolean _force`

- `Boolean _needLog`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Withdraw : ActionNode
{
	private Boolean _withdrawSource; // 0x10
	private Boolean _switchToDeadState; // 0x11
	private Boolean _force; // 0x12
	private Boolean _needLog; // 0x13
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0eb08 VA: 0x7594526b08
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0eb70 VA: 0x7594526b70
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0ecd4 VA: 0x7594526cd4
	public Void .ctor() { }
}
```