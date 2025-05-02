# BlinkNode

**Namespace:** ` `


## Fields

- `Boolean _toNextCheckpoint`

- `Boolean _toMapPosition`

- `Boolean _useNewRouteBeforeBlink`

- `String _branchId`

- `Boolean _useAnimSpeed`

- `Boolean _withoutSwitchToBlinkState`

- `Boolean _skipDisappearCheckpoint`

- `Boolean _forceSetDisappear`

- `Boolean _forceToMapPosition`


## Properties

- `Boolean skipDisappearCheckpoint`


## Methods

- `Boolean get_skipDisappearCheckpoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class BlinkNode : ActionNode
{
	private Boolean _toNextCheckpoint; // 0x10
	private Boolean _toMapPosition; // 0x11
	private Boolean _useNewRouteBeforeBlink; // 0x12
	private String _branchId; // 0x18
	private Boolean _useAnimSpeed; // 0x20
	private Boolean _withoutSwitchToBlinkState; // 0x21
	private Boolean _skipDisappearCheckpoint; // 0x22
	private Boolean _forceSetDisappear; // 0x23
	private Boolean _forceToMapPosition; // 0x24
	private static DelegateBridge __Hotfix0_get_skipDisappearCheckpoint; // 0x0
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x8
	private static DelegateBridge __Hotfix0_Execute; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Boolean skipDisappearCheckpoint { get; }
	public override SourceType allowedSource { get; }

	// RVA: 0x1f8f534 VA: 0x75945a7534
	public Boolean get_skipDisappearCheckpoint() { }
	// RVA: 0x1f8f59c VA: 0x75945a759c
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f8f604 VA: 0x75945a7604
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f8fa68 VA: 0x75945a7a68
	public Void .ctor() { }
}
```