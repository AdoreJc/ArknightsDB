# TemplateTrapGroupViewModel

**Namespace:** `Torappu.UI.TemplateTrap`


## Fields

- `String domainId`

- `Int32 maxSelectCount`

- `String m_domainId`


## Methods

- `Void InitViewModelByDomainId(String)`

- `Void ApplySelect(Int32, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateTrap
public class TemplateTrapGroupViewModel : IHotfixable
{
	public String domainId; // 0x10
	public ListDict`2 trapDict; // 0x18
	public Int32 maxSelectCount; // 0x20
	private String m_domainId; // 0x28
	private static DelegateBridge __Hotfix0_GetSelectedTrapViewModel; // 0x0
	private static DelegateBridge __Hotfix0_InitViewModelByDomainId; // 0x8
	private static DelegateBridge __Hotfix0_ApplySelect; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x234f218 VA: 0x7594967218
	public ListDict`2 GetSelectedTrapViewModel() { }
	// RVA: 0x2350acc VA: 0x7594968acc
	public Void InitViewModelByDomainId(String domainId) { }
	// RVA: 0x2351120 VA: 0x7594969120
	public Void ApplySelect(Int32 index, String id) { }
	// RVA: 0x2350a08 VA: 0x7594968a08
	public Void .ctor() { }
}
```