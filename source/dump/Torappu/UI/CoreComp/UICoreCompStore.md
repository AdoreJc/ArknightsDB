# UICoreCompStore

**Namespace:** `Torappu.UI.CoreComp`


## Methods

- `Void Register(TComp)`

- `Void Unregister(TComp)`

- `TComp FindCompFrom(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CoreComp
public class UICoreCompStore`1 : SingletonInScene`1
{
	private Dictionary`2 m_store; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Register; // 0x0
	private static DelegateBridge __Hotfix0_Unregister; // 0x0
	private static DelegateBridge __Hotfix0_FindCompFrom; // 0x0


	// RVA: 0x VA: 0x0
	private Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void Register(TComp comp) { }
	// RVA: 0x VA: 0x0
	public Void Unregister(TComp comp) { }
	// RVA: 0x VA: 0x0
	public TComp FindCompFrom(Transform current) { }
}
```