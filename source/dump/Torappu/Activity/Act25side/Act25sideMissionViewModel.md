# Act25sideMissionViewModel

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `String m_missionId`

- `String m_areaId`

- `String m_bindStageId`

- `Boolean m_isZone`

- `Int32 m_costCount`

- `Int32 m_transform`

- `Int32 m_progress`

- `String m_progressPicId`

- `String m_desc`


## Properties

- `String missionId`

- `String areaId`

- `String bindStageId`

- `Boolean isZone`

- `Int32 costCount`

- `Int32 transform`

- `Int32 progress`

- `String progressPicId`

- `String desc`


## Methods

- `String get_missionId()`

- `String get_areaId()`

- `String get_bindStageId()`

- `Boolean get_isZone()`

- `Int32 get_costCount()`

- `Int32 get_transform()`

- `Int32 get_progress()`

- `String get_progressPicId()`

- `String get_desc()`

- `Void Load(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideMissionViewModel : IHotfixable
{
	private String m_missionId; // 0x10
	private String m_areaId; // 0x18
	private String m_bindStageId; // 0x20
	private Boolean m_isZone; // 0x28
	private Int32 m_costCount; // 0x2c
	private Int32 m_transform; // 0x30
	private Int32 m_progress; // 0x34
	private String m_progressPicId; // 0x38
	private String m_desc; // 0x40
	private List`1 m_rewards; // 0x48
	private static DelegateBridge __Hotfix0_get_missionId; // 0x0
	private static DelegateBridge __Hotfix0_get_areaId; // 0x8
	private static DelegateBridge __Hotfix0_get_bindStageId; // 0x10
	private static DelegateBridge __Hotfix0_get_isZone; // 0x18
	private static DelegateBridge __Hotfix0_get_costCount; // 0x20
	private static DelegateBridge __Hotfix0_get_transform; // 0x28
	private static DelegateBridge __Hotfix0_get_progress; // 0x30
	private static DelegateBridge __Hotfix0_get_progressPicId; // 0x38
	private static DelegateBridge __Hotfix0_get_desc; // 0x40
	private static DelegateBridge __Hotfix0_get_rewards; // 0x48
	private static DelegateBridge __Hotfix0_Load; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String missionId { get; }
	public String areaId { get; }
	public String bindStageId { get; }
	public Boolean isZone { get; }
	public Int32 costCount { get; }
	public Int32 transform { get; }
	public Int32 progress { get; }
	public String progressPicId { get; }
	public String desc { get; }
	public List`1 rewards { get; }

	// RVA: 0x32870dc VA: 0x759589f0dc
	public String get_missionId() { }
	// RVA: 0x3287144 VA: 0x759589f144
	public String get_areaId() { }
	// RVA: 0x32841a0 VA: 0x759589c1a0
	public String get_bindStageId() { }
	// RVA: 0x3284208 VA: 0x759589c208
	public Boolean get_isZone() { }
	// RVA: 0x32871ac VA: 0x759589f1ac
	public Int32 get_costCount() { }
	// RVA: 0x3287214 VA: 0x759589f214
	public Int32 get_transform() { }
	// RVA: 0x328727c VA: 0x759589f27c
	public Int32 get_progress() { }
	// RVA: 0x32872e4 VA: 0x759589f2e4
	public String get_progressPicId() { }
	// RVA: 0x3283e70 VA: 0x759589be70
	public String get_desc() { }
	// RVA: 0x3284800 VA: 0x759589c800
	public List`1 get_rewards() { }
	// RVA: 0x328734c VA: 0x759589f34c
	public Void Load(String actId, String missionId) { }
	// RVA: 0x3287640 VA: 0x759589f640
	public Void .ctor() { }
}
```