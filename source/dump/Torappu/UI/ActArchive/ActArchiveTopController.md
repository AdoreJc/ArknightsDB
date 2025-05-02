# ActArchiveTopController

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ActArchiveProxy proxy`

- `Boolean m_globalActive`

- `Boolean m_localActive`

- `ActArchiveResHolder m_resHolder`


## Properties

- `ActArchiveResHolder resHolder`


## Methods

- `ActArchiveResHolder get_resHolder()`

- `Void SetGlobalActive(Boolean)`

- `Void SetLocalActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveTopController : MonoBehaviour, IHotfixable
{
	public ActArchiveProxy proxy; // 0x18
	private Boolean m_globalActive; // 0x20
	private Boolean m_localActive; // 0x21
	private ActArchiveResHolder m_resHolder; // 0x28
	private static DelegateBridge __Hotfix0_get_resHolder; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_SetGlobalActive; // 0x10
	private static DelegateBridge __Hotfix0_SetLocalActive; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public ActArchiveResHolder resHolder { get; }

	// RVA: 0x301847c VA: 0x759563047c
	public ActArchiveResHolder get_resHolder() { }
	// RVA: 0x301856c VA: 0x759563056c
	public virtual Void Init(ActArchiveProxy proxy) { }
	// RVA: 0x301808c VA: 0x759563008c
	public Void SetGlobalActive(Boolean active) { }
	// RVA: 0x30185f0 VA: 0x75956305f0
	public Void SetLocalActive(Boolean active) { }
	// RVA: 0x301869c VA: 0x759563069c
	public Void .ctor() { }
}
```