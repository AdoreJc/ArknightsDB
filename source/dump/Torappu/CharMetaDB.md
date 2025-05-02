# CharMetaDB

**Namespace:** `Torappu`


## Methods

- `Void _InitSpCharInfo()`

- `String GetSpCharGroupByCharId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharMetaDB : ConstTable`2
{
	private Dictionary`2 m_spCharGroupMap; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0__InitSpCharInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetSpCharGroupByCharId; // 0x10
	private static DelegateBridge __Hotfix0_GetSpCharIdsByCharId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31ea3d0 VA: 0x75958023d0
	protected override Void OnInit() { }
	// RVA: 0x31ea458 VA: 0x7595802458
	private Void _InitSpCharInfo() { }
	// RVA: 0x31ea6d0 VA: 0x75958026d0
	public String GetSpCharGroupByCharId(String charId) { }
	// RVA: 0x31ea7dc VA: 0x75958027dc
	public List`1 GetSpCharIdsByCharId(String charId) { }
	// RVA: 0x31ea8dc VA: 0x75958028dc
	public Void .ctor() { }
}
```