# Act25sideResearchViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String m_actId`

- `Int32 m_researchCount`

- `String m_selectedAreaId`

- `Boolean isInit`

- `Boolean isMax`

- `Boolean isAllComplete`

- `Boolean isEnd`


## Properties

- `Int32 researchCount`

- `String selectedAreaId`


## Methods

- `Int32 get_researchCount()`

- `String get_selectedAreaId()`

- `Void LoadData(String)`

- `Void _UpdateAreaNewTrackPoint(String)`

- `Void SetSelectAreaId(String)`

- `Act25sideAreaViewModel GetSelectedArea()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchViewModel : IHotfixable
{
	private String m_actId; // 0x10
	private ListDict`2 m_areaViewModels; // 0x18
	private Int32 m_researchCount; // 0x20
	private String m_selectedAreaId; // 0x28
	public Boolean isInit; // 0x30
	public Boolean isMax; // 0x31
	public Boolean isAllComplete; // 0x32
	public Boolean isEnd; // 0x33
	private static DelegateBridge __Hotfix0_get_areaViewModels; // 0x0
	private static DelegateBridge __Hotfix0_get_researchCount; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedAreaId; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0__UpdateAreaNewTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0_SetSelectAreaId; // 0x28
	private static DelegateBridge __Hotfix0_GetSelectedArea; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public ListDict`2 areaViewModels { get; }
	public Int32 researchCount { get; }
	public String selectedAreaId { get; }

	// RVA: 0x3287dcc VA: 0x759589fdcc
	public ListDict`2 get_areaViewModels() { }
	// RVA: 0x3287e34 VA: 0x759589fe34
	public Int32 get_researchCount() { }
	// RVA: 0x3287e9c VA: 0x759589fe9c
	public String get_selectedAreaId() { }
	// RVA: 0x3287f04 VA: 0x759589ff04
	public Void LoadData(String actId) { }
	// RVA: 0x3288434 VA: 0x75958a0434
	private Void _UpdateAreaNewTrackPoint(String areaId) { }
	// RVA: 0x32883a4 VA: 0x75958a03a4
	public Void SetSelectAreaId(String areaId) { }
	// RVA: 0x3288548 VA: 0x75958a0548
	public Act25sideAreaViewModel GetSelectedArea() { }
	// RVA: 0x3288628 VA: 0x75958a0628
	public Void .ctor() { }
}
```