# PlayBGM

**Namespace:** ` `


## Fields

- `Boolean _needSourceStateRunning`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayBGM : ActionNode
{
	private Boolean _needSourceStateRunning; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f9995c VA: 0x75945b195c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f999c4 VA: 0x75945b19c4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f99b38 VA: 0x75945b1b38
	public Void .ctor() { }
}
```