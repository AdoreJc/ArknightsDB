# SandboxV2DungeonMonthModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String <topic>k__BackingField`

- `Int32 <activeRushIdx>k__BackingField`

- `Int32 <selectedRushIdx>k__BackingField`

- `TimeSpan <remainTime>k__BackingField`

- `UpdateStatus <updateStatus>k__BackingField`

- `String <desc>k__BackingField`

- `Single <portableHomeHpRatio>k__BackingField`


## Properties

- `String topic`

- `Int32 activeRushIdx`

- `Int32 selectedRushIdx`

- `RushModel selectdRush`

- `TimeSpan remainTime`

- `UpdateStatus updateStatus`

- `String desc`

- `Single portableHomeHpRatio`


## Methods

- `String get_topic()`

- `Void set_topic(String)`

- `Void set_allRushes(List`1)`

- `Int32 get_activeRushIdx()`

- `Void set_activeRushIdx(Int32)`

- `Int32 get_selectedRushIdx()`

- `Void set_selectedRushIdx(Int32)`

- `RushModel get_selectdRush()`

- `TimeSpan get_remainTime()`

- `Void set_remainTime(TimeSpan)`

- `UpdateStatus get_updateStatus()`

- `Void set_updateStatus(UpdateStatus)`

- `String get_desc()`

- `Void set_desc(String)`

- `Single get_portableHomeHpRatio()`

- `Void set_portableHomeHpRatio(Single)`

- `Void Load(String, SandboxV2DungeonHomePortableNodeViewModel)`

- `Void NextRush()`

- `Void PrevRush()`

- `Void TryToSelectRushById(String)`

- `Void TryToSelectCurrentMonthRush()`

- `Void _SelectByOffset(Int32)`

- `Void _SelectByIndex(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonMonthModel : IHotfixable
{
	private String <topic>k__BackingField; // 0x10
	private List`1 <allRushes>k__BackingField; // 0x18
	private Int32 <activeRushIdx>k__BackingField; // 0x20
	private Int32 <selectedRushIdx>k__BackingField; // 0x24
	private TimeSpan <remainTime>k__BackingField; // 0x28
	private UpdateStatus <updateStatus>k__BackingField; // 0x30
	private String <desc>k__BackingField; // 0x38
	private Single <portableHomeHpRatio>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_topic; // 0x0
	private static DelegateBridge __Hotfix0_set_topic; // 0x8
	private static DelegateBridge __Hotfix0_get_allRushes; // 0x10
	private static DelegateBridge __Hotfix0_set_allRushes; // 0x18
	private static DelegateBridge __Hotfix0_get_activeRushIdx; // 0x20
	private static DelegateBridge __Hotfix0_set_activeRushIdx; // 0x28
	private static DelegateBridge __Hotfix0_get_selectedRushIdx; // 0x30
	private static DelegateBridge __Hotfix0_set_selectedRushIdx; // 0x38
	private static DelegateBridge __Hotfix0_get_selectdRush; // 0x40
	private static DelegateBridge __Hotfix0_get_remainTime; // 0x48
	private static DelegateBridge __Hotfix0_set_remainTime; // 0x50
	private static DelegateBridge __Hotfix0_get_updateStatus; // 0x58
	private static DelegateBridge __Hotfix0_set_updateStatus; // 0x60
	private static DelegateBridge __Hotfix0_get_desc; // 0x68
	private static DelegateBridge __Hotfix0_set_desc; // 0x70
	private static DelegateBridge __Hotfix0_get_portableHomeHpRatio; // 0x78
	private static DelegateBridge __Hotfix0_set_portableHomeHpRatio; // 0x80
	private static DelegateBridge __Hotfix0_Load; // 0x88
	private static DelegateBridge __Hotfix0_LoadEnemyIdListByRushGroup; // 0x90
	private static DelegateBridge __Hotfix0_NextRush; // 0x98
	private static DelegateBridge __Hotfix0_PrevRush; // 0xa0
	private static DelegateBridge __Hotfix0_TryToSelectRushById; // 0xa8
	private static DelegateBridge __Hotfix0_TryToSelectCurrentMonthRush; // 0xb0
	private static DelegateBridge __Hotfix0__SelectByOffset; // 0xb8
	private static DelegateBridge __Hotfix0__SelectByIndex; // 0xc0
	private static DelegateBridge __Hotfix0_CalculateMonthBrief; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public String topic { get; set; }
	public List`1 allRushes { get; set; }
	public Int32 activeRushIdx { get; set; }
	public Int32 selectedRushIdx { get; set; }
	public RushModel selectdRush { get; }
	public TimeSpan remainTime { get; set; }
	public UpdateStatus updateStatus { get; set; }
	public String desc { get; set; }
	public Single portableHomeHpRatio { get; set; }

	// RVA: 0x252eadc VA: 0x7594b46adc
	public String get_topic() { }
	// RVA: 0x252eb44 VA: 0x7594b46b44
	private Void set_topic(String value) { }
	// RVA: 0x252ebc8 VA: 0x7594b46bc8
	public List`1 get_allRushes() { }
	// RVA: 0x252ec30 VA: 0x7594b46c30
	private Void set_allRushes(List`1 value) { }
	// RVA: 0x252ecb4 VA: 0x7594b46cb4
	public Int32 get_activeRushIdx() { }
	// RVA: 0x252ed1c VA: 0x7594b46d1c
	private Void set_activeRushIdx(Int32 value) { }
	// RVA: 0x252ed98 VA: 0x7594b46d98
	public Int32 get_selectedRushIdx() { }
	// RVA: 0x252ee00 VA: 0x7594b46e00
	private Void set_selectedRushIdx(Int32 value) { }
	// RVA: 0x252ee7c VA: 0x7594b46e7c
	public RushModel get_selectdRush() { }
	// RVA: 0x252ef18 VA: 0x7594b46f18
	public TimeSpan get_remainTime() { }
	// RVA: 0x252ef80 VA: 0x7594b46f80
	private Void set_remainTime(TimeSpan value) { }
	// RVA: 0x252effc VA: 0x7594b46ffc
	public UpdateStatus get_updateStatus() { }
	// RVA: 0x252f064 VA: 0x7594b47064
	private Void set_updateStatus(UpdateStatus value) { }
	// RVA: 0x252f0e0 VA: 0x7594b470e0
	public String get_desc() { }
	// RVA: 0x252f148 VA: 0x7594b47148
	private Void set_desc(String value) { }
	// RVA: 0x252f1cc VA: 0x7594b471cc
	public Single get_portableHomeHpRatio() { }
	// RVA: 0x252f234 VA: 0x7594b47234
	private Void set_portableHomeHpRatio(Single value) { }
	// RVA: 0x252f2b0 VA: 0x7594b472b0
	public Void Load(String topicId, SandboxV2DungeonHomePortableNodeViewModel portableHomeModel) { }
	// RVA: 0x252faec VA: 0x7594b47aec
	public List`1 LoadEnemyIdListByRushGroup(String rushGroupKey) { }
	// RVA: 0x2530048 VA: 0x7594b48048
	public Void NextRush() { }
	// RVA: 0x253013c VA: 0x7594b4813c
	public Void PrevRush() { }
	// RVA: 0x25301a8 VA: 0x7594b481a8
	public Void TryToSelectRushById(String rushId) { }
	// RVA: 0x25302d8 VA: 0x7594b482d8
	public Void TryToSelectCurrentMonthRush() { }
	// RVA: 0x25300b4 VA: 0x7594b480b4
	private Void _SelectByOffset(Int32 offset) { }
	// RVA: 0x2530368 VA: 0x7594b48368
	private Void _SelectByIndex(Int32 index) { }
	// RVA: 0x2530460 VA: 0x7594b48460
	public static SandboxV2DungeonMonthBrief CalculateMonthBrief(PlayerSandboxV2 playerData, SandboxV2Data dataBase) { }
	// RVA: 0x2530838 VA: 0x7594b48838
	public Void .ctor() { }
}
```