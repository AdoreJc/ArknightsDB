# HandBookV2MissionTrackPoint

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Boolean m_availFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2MissionTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_availFlag; // 0x10
	private Dictionary`2 m_forceId2FavorSumMap; // 0x18
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetTrackPointState; // 0x10
	private static DelegateBridge __Hotfix0__GetTrackPointStateUsingMap; // 0x18
	private static DelegateBridge __Hotfix0__RefreshFavorSumMap; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isShow { get; }

	// RVA: 0x2ede374 VA: 0x75954f6374
	public Boolean get_isShow() { }
	// RVA: 0x2ede3dc VA: 0x75954f63dc
	public Void UpdateState(Object param) { }
	// RVA: 0x2edeec0 VA: 0x75954f6ec0
	public static Boolean GetTrackPointState(Dictionary`2 favorMap) { }
	// RVA: 0x2edebf0 VA: 0x75954f6bf0
	private static Boolean _GetTrackPointStateUsingMap(Dictionary`2 forceId2FavorSumMap) { }
	// RVA: 0x2ede4cc VA: 0x75954f64cc
	private static Void _RefreshFavorSumMap(Dictionary`2 forceId2FavorSumMap) { }
	// RVA: 0x2edef30 VA: 0x75954f6f30
	public Void .ctor() { }
}
```