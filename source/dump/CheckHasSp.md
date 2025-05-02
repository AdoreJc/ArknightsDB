# CheckHasSp

**Namespace:** ` `


## Fields

- `ActionTargetType _ownerType`

- `Int32 _checkHasSp`

- `String _checkKey`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckHasSp : ActionNode
{
	private ActionTargetType _ownerType; // 0x10
	private Int32 _checkHasSp; // 0x14
	private String _checkKey; // 0x18
	private CompareType _condType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f286b0 VA: 0x75945406b0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f28718 VA: 0x7594540718
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f288fc VA: 0x75945408fc
	public Void .ctor() { }
}
```