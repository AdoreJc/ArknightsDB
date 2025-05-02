# CoroutineSimulator

**Namespace:** `Torappu.Battle`


## Fields

- `UInt64 m_uidCounter`


## Methods

- `Void SimulateTick()`

- `Void Reset()`

- `InternalId StartCoroutine(MonoBehaviour, IEnumerator)`

- `Boolean StopCoroutine(InternalId)`

- `Void StopAllCoroutines(MonoBehaviour)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CoroutineSimulator
{
	private UInt64 m_uidCounter; // 0x10
	private Dictionary`2 m_pendingDict; // 0x18
	private List`1 m_pendingList; // 0x20
	private List`1 m_cachedList; // 0x28


	// RVA: 0x3f661c0 VA: 0x759657e1c0
	public Void SimulateTick() { }
	// RVA: 0x3f66660 VA: 0x759657e660
	public Void Reset() { }
	// RVA: 0x3f666e8 VA: 0x759657e6e8
	public InternalId StartCoroutine(MonoBehaviour mono, IEnumerator routine) { }
	// RVA: 0x3f66970 VA: 0x759657e970
	public Boolean StopCoroutine(InternalId id) { }
	// RVA: 0x3f66a78 VA: 0x759657ea78
	public Void StopAllCoroutines(MonoBehaviour mono) { }
	// RVA: 0x3f66bb0 VA: 0x759657ebb0
	public Void .ctor() { }
}
```