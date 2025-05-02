# LogExtraBattleInfoForModifierRealDelta

**Namespace:** ` `


## Fields

- `ActionTargetType _target`

- `String _key`

- `Boolean _cacheLogKey`

- `String m_cachedKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class LogExtraBattleInfoForModifierRealDelta : ActionNode
{
	private ActionTargetType _target; // 0x10
	private String _key; // 0x18
	private Boolean _cacheLogKey; // 0x20
	private String m_cachedKey; // 0x28
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1eeb5b8 VA: 0x75945035b8
	public override SourceType get_allowedSource() { }
	// RVA: 0x1eeb620 VA: 0x7594503620
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1eeb9cc VA: 0x75945039cc
	public Void .ctor() { }
}
```