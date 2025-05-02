# Follower3D

**Namespace:** `Torappu`


## Fields

- `Vector3 _moveThreshold`

- `Boolean _inactiveWhenUnFollow`

- `Transform m_target`

- `Vector3 m_offset`

- `Vector3 m_lastPos`


## Methods

- `Void Follow(Transform, Vector3)`

- `Void UnFollow(Transform)`

- `Void UnFollow()`

- `Void Update()`

- `Vector3 _GetTargetPosition()`

- `Void _SetPosition(Vector3)`

- `Single _GetValue(Single, Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class Follower3D : MonoBehaviour
{
	private Vector3 _moveThreshold; // 0x18
	private Boolean _inactiveWhenUnFollow; // 0x24
	private Transform m_target; // 0x28
	private Vector3 m_offset; // 0x30
	private Vector3 m_lastPos; // 0x3c


	// RVA: 0x2f46e58 VA: 0x759555ee58
	public Void Follow(Transform target, Vector3 offset) { }
	// RVA: 0x2f46f60 VA: 0x759555ef60
	public Void UnFollow(Transform target) { }
	// RVA: 0x2f46fe8 VA: 0x759555efe8
	public Void UnFollow() { }
	// RVA: 0x2f47044 VA: 0x759555f044
	private Void Update() { }
	// RVA: 0x2f46efc VA: 0x759555eefc
	private Vector3 _GetTargetPosition() { }
	// RVA: 0x2f46f18 VA: 0x759555ef18
	private Void _SetPosition(Vector3 pos) { }
	// RVA: 0x2f47118 VA: 0x759555f118
	private Single _GetValue(Single newVal, Single oldVal, Single threshold) { }
	// RVA: 0x2f47128 VA: 0x759555f128
	public Void .ctor() { }
}
```