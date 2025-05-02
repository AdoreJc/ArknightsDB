# SandboxV2DungeonCullController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonCameraController _cameraController`


## Methods

- `Void Watch(ISandboxV2DungeonCullElement)`

- `Void Unwatch(ISandboxV2DungeonCullElement)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCullController : MonoBehaviour, IHotfixable
{
	private SandboxV2DungeonCameraController _cameraController; // 0x18
	private static DelegateBridge __Hotfix0_Watch; // 0x0
	private static DelegateBridge __Hotfix0_Unwatch; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2512138 VA: 0x7594b2a138
	public Void Watch(ISandboxV2DungeonCullElement element) { }
	// RVA: 0x25121c4 VA: 0x7594b2a1c4
	public Void Unwatch(ISandboxV2DungeonCullElement element) { }
	// RVA: 0x2512250 VA: 0x7594b2a250
	public Void .ctor() { }
}
```