# KnockBackWithDirection

**Namespace:** ` `


## Fields

- `Direction _direction`

- `Boolean _useSourceDirection`

- `Int32 _defaultForceLevel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class KnockBackWithDirection : ActionNode
{
	private Direction _direction; // 0x10
	private Boolean _useSourceDirection; // 0x14
	private Int32 _defaultForceLevel; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7591c VA: 0x759458d91c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f75984 VA: 0x759458d984
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f75ca8 VA: 0x759458dca8
	public Void .ctor() { }
}
```