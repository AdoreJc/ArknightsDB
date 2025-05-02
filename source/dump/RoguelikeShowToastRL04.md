# RoguelikeShowToastRL04

**Namespace:** ` `


## Fields

- `ToastTypeRL04 _toastTypeRL04`

- `Single _lastTime`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RoguelikeShowToastRL04 : ActionNode
{
	private ToastTypeRL04 _toastTypeRL04; // 0x10
	private Single _lastTime; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f807dc VA: 0x75945987dc
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f80844 VA: 0x7594598844
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f80a40 VA: 0x7594598a40
	public Void .ctor() { }
}
```