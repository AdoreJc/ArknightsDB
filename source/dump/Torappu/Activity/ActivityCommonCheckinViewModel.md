# ActivityCommonCheckinViewModel

**Namespace:** `Torappu.Activity`


## Fields

- `String activityId`

- `Int64 apOutTimeStamp`

- `String openTimeStr`

- `PlayerCheckinOnlyTypeActivity playerInfo`

- `Boolean isWithDynCheckin`

- `Boolean needDynViewByPlayerData`

- `DynCheckInDailyInfo currentCheckinInfo`

- `DynamicCheckInData m_dynamicCheckInData`


## Properties

- `DynamicCheckInData dynCheckinData`


## Methods

- `DynamicCheckInData get_dynCheckinData()`

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCommonCheckinViewModel : IHotfixable
{
	public String activityId; // 0x10
	public Dictionary`2 normalCheckinDict; // 0x18
	public Int64 apOutTimeStamp; // 0x20
	public String openTimeStr; // 0x28
	public PlayerCheckinOnlyTypeActivity playerInfo; // 0x30
	public Boolean isWithDynCheckin; // 0x38
	public Boolean needDynViewByPlayerData; // 0x39
	public DynCheckInDailyInfo currentCheckinInfo; // 0x40
	private DynamicCheckInData m_dynamicCheckInData; // 0x48
	private List`1 m_extraCheckinList; // 0x50
	private static DelegateBridge __Hotfix0_get_dynCheckinData; // 0x0
	private static DelegateBridge __Hotfix0_get_dynOptionInfoDict; // 0x8
	private static DelegateBridge __Hotfix0_get_dynOptionRewardItemDict; // 0x10
	private static DelegateBridge __Hotfix0_get_dynCheckInDict; // 0x18
	private static DelegateBridge __Hotfix0_get_extraCheckInList; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0__GetApItemOutTime; // 0x30
	private static DelegateBridge __Hotfix0__GeneOpenTimeStr; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public DynamicCheckInData dynCheckinData { get; }
	public Dictionary`2 dynOptionInfoDict { get; }
	public Dictionary`2 dynOptionRewardItemDict { get; }
	public Dictionary`2 dynCheckInDict { get; }
	public List`1 extraCheckInList { get; }

	// RVA: 0x30d2000 VA: 0x75956ea000
	public DynamicCheckInData get_dynCheckinData() { }
	// RVA: 0x30d2068 VA: 0x75956ea068
	public Dictionary`2 get_dynOptionInfoDict() { }
	// RVA: 0x30d20e0 VA: 0x75956ea0e0
	public Dictionary`2 get_dynOptionRewardItemDict() { }
	// RVA: 0x30d2158 VA: 0x75956ea158
	public Dictionary`2 get_dynCheckInDict() { }
	// RVA: 0x30d21d0 VA: 0x75956ea1d0
	public List`1 get_extraCheckInList() { }
	// RVA: 0x30ce474 VA: 0x75956e6474
	public Void LoadData(String actId) { }
	// RVA: 0x30d25fc VA: 0x75956ea5fc
	private static Int64 _GetApItemOutTime(Dictionary`2 apSupplyOutOfDateDict) { }
	// RVA: 0x30d2238 VA: 0x75956ea238
	private static String _GeneOpenTimeStr(String actId) { }
	// RVA: 0x30cf3cc VA: 0x75956e73cc
	public Void .ctor() { }
}
```