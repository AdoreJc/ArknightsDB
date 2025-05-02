# ConsumeTimeline

**Namespace:** ` `


## Fields

- `String _timelineKey`

- `String m_blackboardKey`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ConsumeTimeline : ActionNode
{
	private String _timelineKey; // 0x10
	private String m_blackboardKey; // 0x18
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f1679c VA: 0x759452e79c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f16804 VA: 0x759452e804
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f16914 VA: 0x759452e914
	public Void .ctor() { }
}
```