# CheckDynamicBuffTileModeInEnum

**Namespace:** ` `


## Fields

- `Boolean _exclude`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDynamicBuffTileModeInEnum : ActionNode
{
	private Int32[] _modes; // 0x10
	private Boolean _exclude; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fe1bd4 VA: 0x75945f9bd4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fe1c3c VA: 0x75945f9c3c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fe1ddc VA: 0x75945f9ddc
	public Void .ctor() { }
}
```