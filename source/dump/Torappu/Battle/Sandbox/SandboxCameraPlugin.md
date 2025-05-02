# SandboxCameraPlugin

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `SandboxMoveCameraAVGCommand m_moveCameraAVGCommand`

- `SandboxLockCameraAVGCommand m_lockCameraAVGCommand`


## Methods

- `Void <>xLuaBaseProxy__InitIfNot()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxCameraPlugin : DraggableCameraPlugin
{
	private SandboxMoveCameraAVGCommand m_moveCameraAVGCommand; // 0xc0
	private SandboxLockCameraAVGCommand m_lockCameraAVGCommand; // 0xc8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1dff7ac VA: 0x75944177ac
	protected override Void _InitIfNot() { }
	// RVA: 0x1dff8d8 VA: 0x75944178d8
	protected override Void OnDestroy() { }
	// RVA: 0x1dff9ac VA: 0x75944179ac
	public Void .ctor() { }
	// RVA: 0x1dffa98 VA: 0x7594417a98
	private Void <>xLuaBaseProxy__InitIfNot() { }
	// RVA: 0x1dffaa0 VA: 0x7594417aa0
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```