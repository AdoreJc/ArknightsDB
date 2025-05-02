# ArchookTraitAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `MountPointType _rotatepoint`

- `MountPointType _hookpoint`

- `Boolean m_isCW`

- `Boolean m_isCircle`

- `Boolean m_currentCW`

- `FP m_curAngle`

- `FixedPosition m_direction`

- `FP m_rotateSpeed`

- `FP m_minAngle`

- `FP m_maxAngle`

- `FP m_rotateZ`

- `Transform m_rotateTransform`

- `Transform m_hookTransform`


## Properties

- `Vector2 direction`


## Methods

- `Vector2 get_direction()`

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Void <>xLuaBaseProxy_DoAttach(Entity)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ArchookTraitAbility : PassiveBuffAbility
{
	private const Int32 MAX_ANGLE; // 0x0
	private MountPointType _rotatepoint; // 0x110
	private MountPointType _hookpoint; // 0x114
	private Boolean m_isCW; // 0x118
	private Boolean m_isCircle; // 0x119
	private Boolean m_currentCW; // 0x11a
	private FP m_curAngle; // 0x120
	private FixedPosition m_direction; // 0x128
	private FP m_rotateSpeed; // 0x150
	private FP m_minAngle; // 0x158
	private FP m_maxAngle; // 0x160
	private FP m_rotateZ; // 0x168
	private ObjectPtr`1 m_character; // 0x170
	private Transform m_rotateTransform; // 0x180
	private Transform m_hookTransform; // 0x188
	private static DelegateBridge __Hotfix0_get_direction; // 0x0
	private static DelegateBridge __Hotfix0_DoSetData; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Vector2 direction { get; }

	// RVA: 0x1e6640c VA: 0x759447e40c
	public Vector2 get_direction() { }
	// RVA: 0x1e66474 VA: 0x759447e474
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1e66afc VA: 0x759447eafc
	protected override Void DoAttach(Entity owner) { }
	// RVA: 0x1e66c70 VA: 0x759447ec70
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e670c8 VA: 0x759447f0c8
	public Void .ctor() { }
	// RVA: 0x1e67138 VA: 0x759447f138
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1e67160 VA: 0x759447f160
	private Void <>xLuaBaseProxy_DoAttach(Entity P0) { }
	// RVA: 0x1e67168 VA: 0x759447f168
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```