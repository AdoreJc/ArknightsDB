# Act13sideDailySearchViewModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `String selectOrgId`

- `ItemBundle selectMatItem`

- `String m_actId`

- `Int32 m_searchCount`


## Properties

- `String actId`

- `Int32 searchCount`


## Methods

- `String get_actId()`

- `Int32 get_searchCount()`

- `Void Init(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailySearchViewModel : IHotfixable
{
	public String selectOrgId; // 0x10
	public ItemBundle selectMatItem; // 0x18
	public List`1 orgList; // 0x20
	public List`1 matList; // 0x28
	private String m_actId; // 0x30
	private Int32 m_searchCount; // 0x38
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_get_searchCount; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String actId { get; }
	public Int32 searchCount { get; }

	// RVA: 0x3439354 VA: 0x7595a51354
	public String get_actId() { }
	// RVA: 0x34393bc VA: 0x7595a513bc
	public Int32 get_searchCount() { }
	// RVA: 0x3439424 VA: 0x7595a51424
	public Void Init(String actId) { }
	// RVA: 0x3439818 VA: 0x7595a51818
	public Void .ctor() { }
}
```