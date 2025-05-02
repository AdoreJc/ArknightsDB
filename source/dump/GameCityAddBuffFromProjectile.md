# GameCityAddBuffFromProjectile

**Namespace:** ` `


## Fields

- `BuffData _buff`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCityAddBuffFromProjectile : ActionNode
{
	private BuffData _buff; // 0x10
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f55364 VA: 0x759456d364
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f553cc VA: 0x759456d3cc
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f55548 VA: 0x759456d548
	public Void .ctor() { }
}
```