# AutoChessFilterPurchasedCharacterGroupTag

**Namespace:** ` `


## Fields

- `String _groupTag`

- `CompareType _condType`

- `Int32 _valueToCompare`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AutoChessFilterPurchasedCharacterGroupTag : ActionNode
{
	private String _groupTag; // 0x10
	private CompareType _condType; // 0x18
	private Int32 _valueToCompare; // 0x1c
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1ee652c VA: 0x75944fe52c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1ee6594 VA: 0x75944fe594
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1ee68c0 VA: 0x75944fe8c0
	public Void .ctor() { }
}
```