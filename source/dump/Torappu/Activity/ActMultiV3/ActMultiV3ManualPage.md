# ActMultiV3ManualPage

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_actId`


## Properties

- `String activityId`


## Methods

- `String get_activityId()`

- `Void UpdateFriendStatus(String, FriendStatus)`

- `FriendStatus GetFriendStatus(String)`

- `Void UpdateTimeStamp(String, Int64)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualPage : StateEnginePage
{
	private String m_actId; // 0xe8
	private Dictionary`2 m_cachedFriendStatus; // 0xf0
	private Dictionary`2 m_searchTimeStamps; // 0xf8
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_friendStatus; // 0x8
	private static DelegateBridge __Hotfix0_get_searchTimeStamps; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_UpdateFriendStatus; // 0x20
	private static DelegateBridge __Hotfix0_GetFriendStatus; // 0x28
	private static DelegateBridge __Hotfix0_UpdateTimeStamp; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String activityId { get; }
	public Dictionary`2 friendStatus { get; }
	public Dictionary`2 searchTimeStamps { get; }

	// RVA: 0x30f6718 VA: 0x759570e718
	public String get_activityId() { }
	// RVA: 0x30f6780 VA: 0x759570e780
	public Dictionary`2 get_friendStatus() { }
	// RVA: 0x30f67e8 VA: 0x759570e7e8
	public Dictionary`2 get_searchTimeStamps() { }
	// RVA: 0x30f6850 VA: 0x759570e850
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x30f6918 VA: 0x759570e918
	public Void UpdateFriendStatus(String uid, FriendStatus friendStatus) { }
	// RVA: 0x30f69e8 VA: 0x759570e9e8
	public FriendStatus GetFriendStatus(String uid) { }
	// RVA: 0x30f6ab8 VA: 0x759570eab8
	public Void UpdateTimeStamp(String templateId, Int64 timeStamp) { }
	// RVA: 0x30f6b64 VA: 0x759570eb64
	public Void .ctor() { }
	// RVA: 0x30f6c78 VA: 0x759570ec78
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```