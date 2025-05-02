# SwitchSubSpineConfig

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `Boolean _defaultToRandom`

- `String _indexKey`

- `Int32 _index`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SwitchSubSpineConfig : ActionNode
{
	private ActionTargetType _target; // 0x10
	private Boolean _defaultToRandom; // 0x14
	private String _indexKey; // 0x18
	private Int32 _index; // 0x20
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1fd79b4 VA: 0x75945ef9b4
	public override SourceType get_allowedSource() { }
	// RVA: 0x1fd7a1c VA: 0x75945efa1c
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1fd7d08 VA: 0x75945efd08
	public Void .ctor() { }
}
```