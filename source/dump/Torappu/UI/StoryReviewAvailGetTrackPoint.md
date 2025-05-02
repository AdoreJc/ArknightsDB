# StoryReviewAvailGetTrackPoint

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_showFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class StoryReviewAvailGetTrackPoint : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0_GetShowFlag; // 0x10
	private static DelegateBridge __Hotfix0__GetReviewRewardShowFlag; // 0x18
	private static DelegateBridge __Hotfix0__CheckStoryAvailable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isShow { get; }

	// RVA: 0x228b77c VA: 0x75948a377c
	public Boolean get_isShow() { }
	// RVA: 0x228b7e4 VA: 0x75948a37e4
	public Void UpdateState(Object param) { }
	// RVA: 0x228b868 VA: 0x75948a3868
	public static Boolean GetShowFlag() { }
	// RVA: 0x228b8ec VA: 0x75948a38ec
	private static Boolean _GetReviewRewardShowFlag() { }
	// RVA: 0x228bc18 VA: 0x75948a3c18
	private static Boolean _CheckStoryAvailable(StoryReviewGroupClientData db) { }
	// RVA: 0x228bda4 VA: 0x75948a3da4
	public Void .ctor() { }
}
```