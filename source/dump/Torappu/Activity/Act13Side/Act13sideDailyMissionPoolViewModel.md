# Act13sideDailyMissionPoolViewModel

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Int32 m_agenda`

- `Int32 m_boardCount`

- `Int32 m_searchCount`

- `Int32 m_selectedPoolIdx`


## Properties

- `Act13sideDailyMissionItemViewModel selectedModel`

- `Int32 selectedPoolIdx`

- `Int32 agenda`

- `Int32 boardCount`

- `Int32 searchCount`


## Methods

- `Act13sideDailyMissionItemViewModel get_selectedModel()`

- `Int32 get_selectedPoolIdx()`

- `Void set_selectedPoolIdx(Int32)`

- `Int32 get_agenda()`

- `Int32 get_boardCount()`

- `Int32 get_searchCount()`

- `Void LoadData(String)`

- `Void _UpdateMissionIdx()`

- `Void _ClearData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionPoolViewModel : IHotfixable
{
	private Int32 m_agenda; // 0x10
	private Int32 m_boardCount; // 0x14
	private Int32 m_searchCount; // 0x18
	private Int32 m_selectedPoolIdx; // 0x1c
	private List`1 m_missionPoolList; // 0x20
	private static DelegateBridge __Hotfix0_get_missionPoolList; // 0x0
	private static DelegateBridge __Hotfix0_get_selectedModel; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedPoolIdx; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedPoolIdx; // 0x18
	private static DelegateBridge __Hotfix0_get_agenda; // 0x20
	private static DelegateBridge __Hotfix0_get_boardCount; // 0x28
	private static DelegateBridge __Hotfix0_get_searchCount; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0__UpdateMissionIdx; // 0x40
	private static DelegateBridge __Hotfix0__ClearData; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public List`1 missionPoolList { get; }
	public Act13sideDailyMissionItemViewModel selectedModel { get; }
	public Int32 selectedPoolIdx { get; set; }
	public Int32 agenda { get; }
	public Int32 boardCount { get; }
	public Int32 searchCount { get; }

	// RVA: 0x3437154 VA: 0x7595a4f154
	public List`1 get_missionPoolList() { }
	// RVA: 0x34371bc VA: 0x7595a4f1bc
	public Act13sideDailyMissionItemViewModel get_selectedModel() { }
	// RVA: 0x3437244 VA: 0x7595a4f244
	public Int32 get_selectedPoolIdx() { }
	// RVA: 0x34372ac VA: 0x7595a4f2ac
	public Void set_selectedPoolIdx(Int32 value) { }
	// RVA: 0x3437328 VA: 0x7595a4f328
	public Int32 get_agenda() { }
	// RVA: 0x3437390 VA: 0x7595a4f390
	public Int32 get_boardCount() { }
	// RVA: 0x34373f8 VA: 0x7595a4f3f8
	public Int32 get_searchCount() { }
	// RVA: 0x3437460 VA: 0x7595a4f460
	public Void LoadData(String actId) { }
	// RVA: 0x3437d00 VA: 0x7595a4fd00
	private Void _UpdateMissionIdx() { }
	// RVA: 0x34376e4 VA: 0x7595a4f6e4
	private Void _ClearData() { }
	// RVA: 0x3437dac VA: 0x7595a4fdac
	public Void .ctor() { }
}
```