# SafeParentComponent

**Namespace:** `Torappu`


## Methods

- `Void SetParentSafe(Transform, Action`1)`

- `Void CancelSetParent(Transform)`

- `Int32 _GetId(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SafeParentComponent : MonoBehaviour
{
	private ListDict`2 m_cachedChildren; // 0x18


	// RVA: 0x3105ce8 VA: 0x759571dce8
	public Void SetParentSafe(Transform child, Action`1 onChildAdded) { }
	// RVA: 0x3105e84 VA: 0x759571de84
	public Void CancelSetParent(Transform child) { }
	// RVA: 0x3105ef0 VA: 0x759571def0
	protected virtual Void OnEnable() { }
	// RVA: 0x3105e6c VA: 0x759571de6c
	private Int32 _GetId(Transform child) { }
	// RVA: 0x310603c VA: 0x759571e03c
	public Void .ctor() { }
}
```