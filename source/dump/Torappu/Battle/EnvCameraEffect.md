# EnvCameraEffect

**Namespace:** `Torappu.Battle`


## Fields

- `String _cameraEffect`

- `CameraEffect m_cameraEffect`


## Methods

- `Void ManageEffect(String)`

- `Void <>xLuaBaseProxy_OnEnvChanged(String, Entity, Entity)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvCameraEffect : EnvEventExecutor
{
	public List`1 _envStatus; // 0x28
	public List`1 _envFinishStatus; // 0x30
	private String _cameraEffect; // 0x38
	private CameraEffect m_cameraEffect; // 0x40
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x0
	private static DelegateBridge __Hotfix0_ManageEffect; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x401f99c VA: 0x759663799c
	public override Void OnEnvChanged(String status, Entity target, Entity sourceNullable) { }
	// RVA: 0x401fa50 VA: 0x7596637a50
	private Void ManageEffect(String status) { }
	// RVA: 0x401fbfc VA: 0x7596637bfc
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x401fd00 VA: 0x7596637d00
	public Void .ctor() { }
	// RVA: 0x401fd70 VA: 0x7596637d70
	private Void <>xLuaBaseProxy_OnEnvChanged(String P0, Entity P1, Entity P2) { }
	// RVA: 0x401fd78 VA: 0x7596637d78
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
}
```