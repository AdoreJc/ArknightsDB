# RaiseDialogue

**Namespace:** ` `


## Fields

- `Boolean _isAppearDialog`

- `Boolean _doNotCheckSource`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RaiseDialogue : ActionNode
{
	private Boolean _isAppearDialog; // 0x10
	private Boolean _doNotCheckSource; // 0x11
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee915c VA: 0x759450115c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee91c4 VA: 0x75945011c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee93f8 VA: 0x75945013f8
	public Void .ctor() { }
}
```