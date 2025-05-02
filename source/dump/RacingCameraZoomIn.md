# RacingCameraZoomIn

**Namespace:** ` `


## Fields

- `Single _cameraFollowSpeedFactor`

- `Single _zoomDuration`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RacingCameraZoomIn : ActionNode
{
	private Single _cameraFollowSpeedFactor; // 0x10
	private Single _zoomDuration; // 0x14
	private static DelegateBridge __Hotfix0_get_allowedSource; // 0x0
	private static DelegateBridge __Hotfix0_Execute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override SourceType allowedSource { get; }

	// RVA: 0x1f7b708 VA: 0x7594593708
	public override SourceType get_allowedSource() { }
	// RVA: 0x1f7b770 VA: 0x7594593770
	public override Boolean Execute(Blackboard blackboard, SourceType sourceType, ref Snapshot snapshot) { }
	// RVA: 0x1f7b904 VA: 0x7594593904
	public Void .ctor() { }
}
```