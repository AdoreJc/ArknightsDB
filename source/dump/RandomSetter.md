# RandomSetter

**Namespace:** ` `


## Fields

- `String _targetKey`

- `String m_minKey`

- `String m_maxKey`


## Properties

- `String minKey`

- `String maxKey`


## Methods

- `String get_minKey()`

- `String get_maxKey()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RandomSetter : ActionNode
{
	private String _targetKey; // 0x10
	private String m_minKey; // 0x18
	private String m_maxKey; // 0x20
	private static DelegateBridge __Hotfix0_get_minKey; // 0x0
	private static DelegateBridge __Hotfix0_get_maxKey; // 0x8
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x10
	private static DelegateBridge __Hotfix0_Execute; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private String minKey { get; }
	private String maxKey { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f7bbdc VA: 0x7594593bdc
	private String get_minKey() { }
	// RVA: 0x1f7bc8c VA: 0x7594593c8c
	private String get_maxKey() { }
	// RVA: 0x1f7bd3c VA: 0x7594593d3c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7bda4 VA: 0x7594593da4
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7bf30 VA: 0x7594593f30
	public Void .ctor() { }
}
```