# UIFollower

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Vector2 _moveThreshold`

- `Boolean _inactiveWhenUnFollow`

- `Boolean _targetInGameSpace`

- `Transform m_target`

- `Vector2 m_offset`

- `Vector2 m_lastPos`


## Properties

- `Transform target`


## Methods

- `Transform get_target()`

- `Void set_target(Transform)`

- `Void Follow(Transform, Vector2)`

- `Void UnFollow(Transform)`

- `Void UnFollow()`

- `Vector2 _GetTargetPosition()`

- `Void _SetPosition(Vector2)`

- `Single _GetValue(Single, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIFollower : MonoBehaviour, IHotfixable
{
	private Vector2 _moveThreshold; // 0x18
	private Boolean _inactiveWhenUnFollow; // 0x20
	private Boolean _targetInGameSpace; // 0x21
	private Transform m_target; // 0x28
	private Vector2 m_offset; // 0x30
	private Vector2 m_lastPos; // 0x38
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_set_target; // 0x8
	private static DelegateBridge __Hotfix0_Follow; // 0x10
	private static DelegateBridge __Hotfix0_UnFollow; // 0x18
	private static DelegateBridge __Hotfix1_UnFollow; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0__GetTargetPosition; // 0x30
	private static DelegateBridge __Hotfix0__SetPosition; // 0x38
	private static DelegateBridge __Hotfix0__GetValue; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected Transform target { get; set; }

	// RVA: 0x205d844 VA: 0x7594675844
	protected Transform get_target() { }
	// RVA: 0x205d8ac VA: 0x75946758ac
	protected Void set_target(Transform value) { }
	// RVA: 0x205d930 VA: 0x7594675930
	public Void Follow(Transform target, Vector2 offset) { }
	// RVA: 0x205dba4 VA: 0x7594675ba4
	public Void UnFollow(Transform target) { }
	// RVA: 0x205dc6c VA: 0x7594675c6c
	public Void UnFollow() { }
	// RVA: 0x205dd14 VA: 0x7594675d14
	public virtual Void Update() { }
	// RVA: 0x205da24 VA: 0x7594675a24
	private Vector2 _GetTargetPosition() { }
	// RVA: 0x205dae4 VA: 0x7594675ae4
	private Void _SetPosition(Vector2 pos) { }
	// RVA: 0x205de20 VA: 0x7594675e20
	private Single _GetValue(Single newVal, Single oldVal, Single threshold) { }
	// RVA: 0x205dfac VA: 0x7594675fac
	public Void .ctor() { }
}
```