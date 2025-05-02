# SandboxV2DungeonState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonCameraController _cameraController`

- `SandboxV2DungeonController m_controller`

- `UIPage m_page`


## Methods

- `Void _OnJumpToNodeUpgrade(IStateBean)`

- `Void _OnJumpToNodeStagePreview(IStateBean)`

- `Void _OnJumpToNodeDropDetail(IStateBean)`

- `Void _OnJumpToDungeonSquad(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonState : SandboxV2TransparentState
{
	private SandboxV2DungeonCameraController _cameraController; // 0x70
	private SandboxV2DungeonController m_controller; // 0x78
	private UIPage m_page; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToNodeUpgrade; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToNodeStagePreview; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToNodeDropDetail; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToDungeonSquad; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2548c10 VA: 0x7594b60c10
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2548c74 VA: 0x7594b60c74
	protected override Void OnEnter() { }
	// RVA: 0x2548d1c VA: 0x7594b60d1c
	protected override Void OnPause() { }
	// RVA: 0x2548da4 VA: 0x7594b60da4
	protected override Void OnResume() { }
	// RVA: 0x2548e84 VA: 0x7594b60e84
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2549158 VA: 0x7594b61158
	private Void _OnJumpToNodeUpgrade(IStateBean stateBean) { }
	// RVA: 0x2549368 VA: 0x7594b61368
	private Void _OnJumpToNodeStagePreview(IStateBean stateBean) { }
	// RVA: 0x25494d8 VA: 0x7594b614d8
	private Void _OnJumpToNodeDropDetail(IStateBean stateBean) { }
	// RVA: 0x2549760 VA: 0x7594b61760
	private Void _OnJumpToDungeonSquad(IStateBean stateBean) { }
	// RVA: 0x2549964 VA: 0x7594b61964
	public Void .ctor() { }
	// RVA: 0x25499d0 VA: 0x7594b619d0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x25499d4 VA: 0x7594b619d4
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x25499dc VA: 0x7594b619dc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x25499e4 VA: 0x7594b619e4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```