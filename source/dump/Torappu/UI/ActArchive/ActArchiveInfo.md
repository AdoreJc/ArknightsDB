# ActArchiveInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String <archiveId>k__BackingField`

- `Param <archiveParams>k__BackingField`

- `ActArchivePlugin <archivePlugin>k__BackingField`

- `DataBundle <extraPassthroughData>k__BackingField`

- `Boolean m_hasInited`


## Properties

- `String archiveId`

- `Param archiveParams`

- `ActArchivePlugin archivePlugin`

- `DataBundle extraPassthroughData`


## Methods

- `String get_archiveId()`

- `Void set_archiveId(String)`

- `Param get_archiveParams()`

- `Void set_archiveParams(Param)`

- `ActArchivePlugin get_archivePlugin()`

- `Void set_archivePlugin(ActArchivePlugin)`

- `DataBundle get_extraPassthroughData()`

- `Void set_extraPassthroughData(DataBundle)`

- `Void _InitIfNot()`

- `Void LoadData(Param)`

- `Boolean HasArchiveComp(ActArchiveType)`

- `ActArchiveCompInfo GetArchiveComp(ActArchiveType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveInfo : IHotfixable
{
	private String <archiveId>k__BackingField; // 0x10
	private Param <archiveParams>k__BackingField; // 0x18
	private ActArchivePlugin <archivePlugin>k__BackingField; // 0x20
	private DataBundle <extraPassthroughData>k__BackingField; // 0x28
	private Boolean m_hasInited; // 0x30
	private ListDict`2 m_archiveCompInfo; // 0x38
	private static DelegateBridge __Hotfix0_get_archiveId; // 0x0
	private static DelegateBridge __Hotfix0_set_archiveId; // 0x8
	private static DelegateBridge __Hotfix0_get_archiveParams; // 0x10
	private static DelegateBridge __Hotfix0_set_archiveParams; // 0x18
	private static DelegateBridge __Hotfix0_get_archivePlugin; // 0x20
	private static DelegateBridge __Hotfix0_set_archivePlugin; // 0x28
	private static DelegateBridge __Hotfix0_get_extraPassthroughData; // 0x30
	private static DelegateBridge __Hotfix0_set_extraPassthroughData; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_GetValidArchiveCompInfo; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge __Hotfix0_HasArchiveComp; // 0x58
	private static DelegateBridge __Hotfix0_GetArchiveComp; // 0x60
	private static DelegateBridge __Hotfix0_GetArchiveTrackpointStatus; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public String archiveId { get; set; }
	public Param archiveParams { get; set; }
	public ActArchivePlugin archivePlugin { get; set; }
	public DataBundle extraPassthroughData { get; set; }

	// RVA: 0x3008888 VA: 0x7595620888
	public String get_archiveId() { }
	// RVA: 0x3018928 VA: 0x7595630928
	private Void set_archiveId(String value) { }
	// RVA: 0x30082b0 VA: 0x75956202b0
	public Param get_archiveParams() { }
	// RVA: 0x30189ac VA: 0x75956309ac
	private Void set_archiveParams(Param value) { }
	// RVA: 0x30076a0 VA: 0x759561f6a0
	public ActArchivePlugin get_archivePlugin() { }
	// RVA: 0x3018a30 VA: 0x7595630a30
	private Void set_archivePlugin(ActArchivePlugin value) { }
	// RVA: 0x3018ab4 VA: 0x7595630ab4
	public DataBundle get_extraPassthroughData() { }
	// RVA: 0x3018b1c VA: 0x7595630b1c
	private Void set_extraPassthroughData(DataBundle value) { }
	// RVA: 0x3018ba0 VA: 0x7595630ba0
	private Void _InitIfNot() { }
	// RVA: 0x3019334 VA: 0x7595631334
	public Dictionary`2 GetValidArchiveCompInfo() { }
	// RVA: 0x3013a6c VA: 0x759562ba6c
	public Void LoadData(Param param) { }
	// RVA: 0x300551c VA: 0x759561d51c
	public Boolean HasArchiveComp(ActArchiveType archiveType) { }
	// RVA: 0x3008ba8 VA: 0x7595620ba8
	public ActArchiveCompInfo GetArchiveComp(ActArchiveType archiveType) { }
	// RVA: 0x VA: 0x0
	public static Boolean GetArchiveTrackpointStatus(String archiveId) { }
	// RVA: 0x30139fc VA: 0x759562b9fc
	public Void .ctor() { }
}
```