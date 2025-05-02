# CheckSanity

**Namespace:** ` `


## Fields

- `Int32 _value`

- `String _valueKey`

- `CompareType _compareType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckSanity : ActionNode
{
	private Int32 _value; // 0x10
	private String _valueKey; // 0x18
	private CompareType _compareType; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7e57c VA: 0x759459657c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7e5e4 VA: 0x75945965e4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7e790 VA: 0x7594596790
	public Void .ctor() { }
}
```