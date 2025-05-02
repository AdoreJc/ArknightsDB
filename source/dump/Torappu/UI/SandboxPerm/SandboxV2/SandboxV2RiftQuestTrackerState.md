# SandboxV2RiftQuestTrackerState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAnimationLocation _enterAnim`

- `SandboxV2RiftQuestTrackerView _view`

- `Boolean m_isInited`

- `Tween m_enterTween`

- `SandboxV2RiftQuestTrackerProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void _PlayEnterAnim()`

- `Void _UpdateData()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftQuestTrackerState : SandboxV2TrackerState
{
	private UIAnimationLocation _enterAnim; // 0x80
	private SandboxV2RiftQuestTrackerView _view; // 0x90
	private Boolean m_isInited; // 0x98
	private Tween m_enterTween; // 0xa0
	private SandboxV2RiftQuestTrackerProperty m_property; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x18
	private static DelegateBridge __Hotfix0__UpdateData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2554cb0 VA: 0x7594b6ccb0
	protected override Void OnEnter() { }
	// RVA: 0x2555008 VA: 0x7594b6d008
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2554d30 VA: 0x7594b6cd30
	private Void _InitIfNot() { }
	// RVA: 0x2554f2c VA: 0x7594b6cf2c
	private Void _PlayEnterAnim() { }
	// RVA: 0x2554dd8 VA: 0x7594b6cdd8
	private Void _UpdateData() { }
	// RVA: 0x25552e4 VA: 0x7594b6d2e4
	public Void .ctor() { }
	// RVA: 0x25553f8 VA: 0x7594b6d3f8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```