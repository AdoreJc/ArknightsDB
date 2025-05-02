# CheckDeathCnt

**Namespace:** ` `


## Fields

- `Int32 _checkFinishCnt`

- `CompareType _condType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CheckDeathCnt : ActionNode
{
	private Int32 _checkFinishCnt; // 0x10
	private CompareType _condType; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f2380c VA: 0x759453b80c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f23874 VA: 0x759453b874
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f23ac8 VA: 0x759453bac8
	public Void .ctor() { }
}
```