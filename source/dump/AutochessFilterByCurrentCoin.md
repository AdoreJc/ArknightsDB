# AutochessFilterByCurrentCoin

**Namespace:** ` `


## Fields

- `CompareType _condType`

- `Int32 _valueToCompare`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutochessFilterByCurrentCoin : ActionNode
{
	private CompareType _condType; // 0x10
	private Int32 _valueToCompare; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee4c18 VA: 0x75944fcc18
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee4c80 VA: 0x75944fcc80
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee4e24 VA: 0x75944fce24
	public Void .ctor() { }
}
```