# FollowDirection

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _useFourDir`

- `Boolean _useOwnerDirection`

- `Boolean _useOwnerMoveDirection`

- `Boolean _leftIsDefault`

- `Boolean _useFaceToInsteadOfFaceVector`

- `Boolean _flipWhenFaceToVertical`

- `Boolean _onlyFollowOnPlay`

- `Boolean _useDirectionLerp`

- `Single _lerpDuration`

- `Vector2 m_sourceDir`

- `Vector2 m_targetDir`

- `Vector2 m_currDir`

- `Single m_currTime`

- `Boolean m_isLerping`


## Properties

- `Boolean useFaceToInsteadOfFaceVector`


## Methods

- `Boolean get_useFaceToInsteadOfFaceVector()`

- `Void Update()`

- `Void UpdateDirection()`

- `Void _FollowDirection(Entity)`

- `Void _LerpDirection(Enemy)`

- `Void <>xLuaBaseProxy_OnRecycle()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FollowDirection : Behaviour
{
	private Boolean _useFourDir; // 0x20
	private Boolean _useOwnerDirection; // 0x21
	private Boolean _useOwnerMoveDirection; // 0x22
	private Boolean _leftIsDefault; // 0x23
	private Boolean _useFaceToInsteadOfFaceVector; // 0x24
	private Boolean _flipWhenFaceToVertical; // 0x25
	private Boolean _onlyFollowOnPlay; // 0x26
	private Boolean _useDirectionLerp; // 0x27
	private Single _lerpDuration; // 0x28
	private Vector2 m_sourceDir; // 0x2c
	private Vector2 m_targetDir; // 0x34
	private Vector2 m_currDir; // 0x3c
	private Single m_currTime; // 0x44
	private Boolean m_isLerping; // 0x48
	private static DelegateBridge __Hotfix0_get_useFaceToInsteadOfFaceVector; // 0x0
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x8
	private static DelegateBridge __Hotfix0_OnPlay; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0_UpdateDirection; // 0x20
	private static DelegateBridge __Hotfix0__FollowDirection; // 0x28
	private static DelegateBridge __Hotfix0__LerpDirection; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean useFaceToInsteadOfFaceVector { get; }

	// RVA: 0x1ffbbe8 VA: 0x7594613be8
	public Boolean get_useFaceToInsteadOfFaceVector() { }
	// RVA: 0x1ffbc50 VA: 0x7594613c50
	public override Void OnRecycle() { }
	// RVA: 0x1ffbd0c VA: 0x7594613d0c
	public override Void OnPlay() { }
	// RVA: 0x1ffbe58 VA: 0x7594613e58
	private Void Update() { }
	// RVA: 0x1ffbd7c VA: 0x7594613d7c
	private Void UpdateDirection() { }
	// RVA: 0x1ffbed4 VA: 0x7594613ed4
	private Void _FollowDirection(Entity entity) { }
	// RVA: 0x1ffc1dc VA: 0x75946141dc
	private Void _LerpDirection(Enemy enemy) { }
	// RVA: 0x1ffc5c4 VA: 0x75946145c4
	public Void .ctor() { }
	// RVA: 0x1ffc68c VA: 0x759461468c
	private Void <>xLuaBaseProxy_OnRecycle() { }
	// RVA: 0x1ffc690 VA: 0x7594614690
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```