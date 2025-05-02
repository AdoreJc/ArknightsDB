# Knockback

**Namespace:** ` `


## Fields

- `Boolean _useSourceDirection`

- `Int32 _decreaseForceLevelWhenNotInDirection`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Knockback : ActionNode
{
	private const Single TOO_CLOSE_TOLERANCE_SQR; // 0x0
	private Boolean _useSourceDirection; // 0x10
	private Int32 _decreaseForceLevelWhenNotInDirection; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7548c VA: 0x759458d48c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f754f4 VA: 0x759458d4f4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f758a0 VA: 0x759458d8a0
	public Void .ctor() { }
}
```