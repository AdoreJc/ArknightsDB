# StartTimeline

**Namespace:** ` `


## Fields

- `String _timelineKey`

- `String m_blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StartTimeline : ActionNode
{
	private String _timelineKey; // 0x10
	private String m_blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f165a0 VA: 0x759452e5a0
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16608 VA: 0x759452e608
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f166fc VA: 0x759452e6fc
	public Void .ctor() { }
}
```