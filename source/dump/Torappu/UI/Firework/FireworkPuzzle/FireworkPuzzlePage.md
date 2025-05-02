# FireworkPuzzlePage

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `String <actId>k__BackingField`


## Properties

- `String actId`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `PlateContent GetPlateContentData(String)`

- `Act38SideServerPuzzleInfo GetServerPuzzleInfo(String)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzlePage : StateEnginePage, IHotfixable
{
	private Dictionary`2 m_puzzleData; // 0xe8
	private Dictionary`2 m_puzzleInfoMap; // 0xf0
	private String <actId>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_GetPlateContentData; // 0x18
	private static DelegateBridge __Hotfix0_GetServerPuzzleInfo; // 0x20
	private static DelegateBridge __Hotfix0_GetUnlockedPuzzleIdList; // 0x28
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String actId { get; set; }

	// RVA: 0x28f85fc VA: 0x7594f105fc
	public String get_actId() { }
	// RVA: 0x28f8664 VA: 0x7594f10664
	private Void set_actId(String value) { }
	// RVA: 0x28f86e8 VA: 0x7594f106e8
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x28f87c4 VA: 0x7594f107c4
	public PlateContent GetPlateContentData(String plateId) { }
	// RVA: 0x28f888c VA: 0x7594f1088c
	public Act38SideServerPuzzleInfo GetServerPuzzleInfo(String puzzleId) { }
	// RVA: 0x28f7500 VA: 0x7594f0f500
	public List`1 GetUnlockedPuzzleIdList() { }
	// RVA: 0x28f78bc VA: 0x7594f0f8bc
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x28f8954 VA: 0x7594f10954
	public Void .ctor() { }
	// RVA: 0x28f89c4 VA: 0x7594f109c4
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```