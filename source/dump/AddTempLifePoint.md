# AddTempLifePoint

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddTempLifePoint : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f0cfd8 VA: 0x7594524fd8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f0d040 VA: 0x7594525040
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f0d17c VA: 0x759452517c
	public Void .ctor() { }
}
```