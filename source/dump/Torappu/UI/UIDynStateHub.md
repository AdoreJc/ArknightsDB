# UIDynStateHub

**Namespace:** `Torappu.UI`


## Methods

- `Void set__dragStatesHere(State[])`

- `Void _InitIfNotRuntime()`

- `String GetStateResPath(DynStateID)`

- `Void OnBeforeSerialize()`

- `Void OnAfterDeserialize()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIDynStateHub : ScriptableObject, ISerializationCallbackReceiver, IHotfixable
{
	private List`1 _states; // 0x18
	private Dictionary`2 m_stateMapRuntime; // 0x20
	private static DelegateBridge __Hotfix0_get__dragStatesHere; // 0x0
	private static DelegateBridge __Hotfix0_set__dragStatesHere; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNotRuntime; // 0x10
	private static DelegateBridge __Hotfix0_GetStateResPath; // 0x18
	private static DelegateBridge __Hotfix0_OnBeforeSerialize; // 0x20
	private static DelegateBridge __Hotfix0_OnAfterDeserialize; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private State[] _dragStatesHere { get; set; }

	// RVA: 0x216761c VA: 0x759477f61c
	private State[] get__dragStatesHere() { }
	// RVA: 0x216769c VA: 0x759477f69c
	private Void set__dragStatesHere(State[] value) { }
	// RVA: 0x2167714 VA: 0x759477f714
	private Void _InitIfNotRuntime() { }
	// RVA: 0x2164008 VA: 0x759477c008
	public String GetStateResPath(DynStateID id) { }
	// RVA: 0x2167888 VA: 0x759477f888
	public Void OnBeforeSerialize() { }
	// RVA: 0x2167af8 VA: 0x759477faf8
	public Void OnAfterDeserialize() { }
	// RVA: 0x2167b5c VA: 0x759477fb5c
	public Void .ctor() { }
}
```