# DataBindSystem

**Namespace:** `Torappu.DataBind`


## Methods

- `Void Update()`

- `Void NotifyToUpdate(IBindProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.DataBind
public class DataBindSystem : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private List`1 m_dirtyProps; // 0x18
	private List`1 m_propsBuffer; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_NotifyToUpdate; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x356e274 VA: 0x7595b86274
	private Void Update() { }
	// RVA: 0x356e4d0 VA: 0x7595b864d0
	public Void NotifyToUpdate(IBindProperty prop) { }
	// RVA: 0x356e5cc VA: 0x7595b865cc
	public Void .ctor() { }
}
```