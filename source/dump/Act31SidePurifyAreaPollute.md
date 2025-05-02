# Act31SidePurifyAreaPollute

**Namespace:** ` `


## Fields

- `ActionTargetType _sourceType`

- `Int32 _addPolluteV`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Act31SidePurifyAreaPollute : ActionNode
{
	private ActionTargetType _sourceType; // 0x10
	private Int32 _addPolluteV; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1edd164 VA: 0x75944f5164
	public override SourceType get_allowedSource() { }
	// RVA: 0x1edd1cc VA: 0x75944f51cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1edd42c VA: 0x75944f542c
	public Void .ctor() { }
}
```