# Follower2D

**Namespace:** `Torappu`


## Fields

- `Vector2 _moveThreshold`

- `Boolean _inactiveWhenUnFollow`

- `Boolean _followOnce`

- `Transform _targetOnStart`

- `Transform m_target`

- `Vector2 m_offset`

- `Vector2 m_lastPos`


## Methods

- `Void Follow(Transform, Vector2)`

- `Void UnFollow(Transform)`

- `Void UnFollow()`

- `Void UpdatePosition()`

- `Vector2 _GetTargetPosition()`

- `Void _SetPosition(Vector2)`

- `Single _GetValue(Single, Single, Single)`

- `Void Update()`

- `Void Start()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class Follower2D : MonoBehaviour
{
	private Vector2 _moveThreshold; // 0x18
	private Boolean _inactiveWhenUnFollow; // 0x20
	private Boolean _followOnce; // 0x21
	private Transform _targetOnStart; // 0x28
	private Transform m_target; // 0x30
	private Vector2 m_offset; // 0x38
	private Vector2 m_lastPos; // 0x40


	// RVA: 0x2f46ab0 VA: 0x759555eab0
	public Void Follow(Transform target, Vector2 offset) { }
	// RVA: 0x2f46ba0 VA: 0x759555eba0
	public Void UnFollow(Transform target) { }
	// RVA: 0x2f46c28 VA: 0x759555ec28
	public Void UnFollow() { }
	// RVA: 0x2f46c84 VA: 0x759555ec84
	public Void UpdatePosition() { }
	// RVA: 0x2f46b20 VA: 0x759555eb20
	private Vector2 _GetTargetPosition() { }
	// RVA: 0x2f46b3c VA: 0x759555eb3c
	private Void _SetPosition(Vector2 pos) { }
	// RVA: 0x2f46d30 VA: 0x759555ed30
	private Single _GetValue(Single newVal, Single oldVal, Single threshold) { }
	// RVA: 0x2f46d40 VA: 0x759555ed40
	private Void Update() { }
	// RVA: 0x2f46d44 VA: 0x759555ed44
	private Void Start() { }
	// RVA: 0x2f46df8 VA: 0x759555edf8
	public Void .ctor() { }
}
```