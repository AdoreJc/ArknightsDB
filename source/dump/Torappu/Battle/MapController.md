# MapController

**Namespace:** `Torappu.Battle`


## Fields

- `Map m_map`


## Properties

- `Map map`


## Methods

- `Map get_map()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MapController : IHotfixable
{
	private Map m_map; // 0x10
	private static DelegateBridge __Hotfix0_get_tag; // 0x0
	private static DelegateBridge __Hotfix0_get_map; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Reset; // 0x20

	public virtual MapTags tag { get; }
	public Map map { get; }

	// RVA: 0x40118bc VA: 0x75966298bc
	public virtual MapTags get_tag() { }
	// RVA: 0x4010a30 VA: 0x7596628a30
	public Map get_map() { }
	// RVA: 0x400b820 VA: 0x7596623820
	public Void .ctor() { }
	// RVA: 0x400b988 VA: 0x7596623988
	public virtual Void Init(Map battleMap) { }
	// RVA: 0x400bdc8 VA: 0x7596623dc8
	public virtual Void Reset() { }
}
```