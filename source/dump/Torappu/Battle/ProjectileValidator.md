# ProjectileValidator

**Namespace:** `Torappu.Battle`


## Fields

- `SideType _targetSide`

- `Boolean _verifyProjectileType`

- `ProjectileType _projectileType`

- `Boolean _graphicExclude`

- `SideType m_targetSideMask`


## Methods

- `Boolean VerifyTarget(Projectile)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ProjectileValidator : MonoBehaviour, IHotfixable
{
	private SideType _targetSide; // 0x18
	private Boolean _verifyProjectileType; // 0x1c
	private ProjectileType _projectileType; // 0x20
	private Boolean _graphicExclude; // 0x24
	private SideType m_targetSideMask; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_VerifyTarget; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1bdba18 VA: 0x75941f3a18
	public virtual Void SetData(Entity owner, Blackboard blackboard) { }
	// RVA: 0x1bdbab4 VA: 0x75941f3ab4
	public Boolean VerifyTarget(Projectile target) { }
	// RVA: 0x1bdbb98 VA: 0x75941f3b98
	public Void .ctor() { }
}
```