# CrisisV2MapExclusionModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_exclusionId`

- `CrisisV2ExclusionData m_exclusionData`


## Properties

- `String defaultSlotId`


## Methods

- `String get_defaultSlotId()`

- `Void Load(String, CrisisV2ExclusionData, CrisisV2MapDetailData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapExclusionModel : IHotfixable
{
	private List`1 m_nodeList; // 0x10
	private String m_exclusionId; // 0x18
	private CrisisV2ExclusionData m_exclusionData; // 0x20
	private static DelegateBridge __Hotfix0_get_defaultSlotId; // 0x0
	private static DelegateBridge __Hotfix0_get_nodeList; // 0x8
	private static DelegateBridge __Hotfix0_Load; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String defaultSlotId { get; }
	public List`1 nodeList { get; }

	// RVA: 0x2bef894 VA: 0x7595207894
	public String get_defaultSlotId() { }
	// RVA: 0x2bf0674 VA: 0x7595208674
	public List`1 get_nodeList() { }
	// RVA: 0x2bf1550 VA: 0x7595209550
	public Void Load(String exclusionId, CrisisV2ExclusionData exclusionData, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bf148c VA: 0x759520948c
	public Void .ctor() { }
}
```