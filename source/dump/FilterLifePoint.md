# FilterLifePoint

**Namespace:** ` `


## Fields

- `CompareType _compareType`

- `Int32 _lifePoint`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class FilterLifePoint : ActionNode
{
	private CompareType _compareType; // 0x10
	private Int32 _lifePoint; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f27fe0 VA: 0x759453ffe0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f28048 VA: 0x7594540048
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f28184 VA: 0x7594540184
	public Void .ctor() { }
}
```