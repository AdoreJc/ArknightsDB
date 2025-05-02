# EnvProjectileToEntity

**Namespace:** `Torappu.Battle`


## Fields

- `String _projectileKey`

- `MountPointType _targetMountPointType`

- `MountPointType _sourceMountPointType`

- `TargetOptions _options`

- `Ability m_ability`


## Methods

- `Void _EmitProjectileToTarget(Entity, Entity)`

- `Void <>xLuaBaseProxy_Init(GlobalEnvSystem)`

- `Void <>xLuaBaseProxy_OnEnvChanged(String, Entity, Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvProjectileToEntity : EnvEventExecutor
{
	public List`1 _envStatus; // 0x28
	private String _projectileKey; // 0x30
	private MountPointType _targetMountPointType; // 0x38
	private MountPointType _sourceMountPointType; // 0x3c
	private TargetOptions _options; // 0x40
	private Ability m_ability; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnEnvChanged; // 0x8
	private static DelegateBridge __Hotfix0__EmitProjectileToTarget; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x40258ec VA: 0x759663d8ec
	public override Void Init(GlobalEnvSystem owner) { }
	// RVA: 0x4025aa8 VA: 0x759663daa8
	public override Void OnEnvChanged(String status, Entity target, Entity sourceNullable) { }
	// RVA: 0x4025c58 VA: 0x759663dc58
	private Void _EmitProjectileToTarget(Entity target, Entity source) { }
	// RVA: 0x4025e80 VA: 0x759663de80
	public Void .ctor() { }
	// RVA: 0x4025ef4 VA: 0x759663def4
	private Void <>xLuaBaseProxy_Init(GlobalEnvSystem P0) { }
	// RVA: 0x4025ef8 VA: 0x759663def8
	private Void <>xLuaBaseProxy_OnEnvChanged(String P0, Entity P1, Entity P2) { }
}
```