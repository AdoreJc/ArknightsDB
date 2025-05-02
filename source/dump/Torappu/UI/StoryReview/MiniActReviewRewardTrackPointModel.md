# MiniActReviewRewardTrackPointModel

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `Boolean m_showFlag`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void UpdateState(Object)`

- `Boolean _GetShowFlag()`

- `Boolean _CheckStoryAvailable(StoryReviewGroupClientData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActReviewRewardTrackPointModel : ITrackPointModel, IHotfixable
{
	private Boolean m_showFlag; // 0x10
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_UpdateState; // 0x8
	private static DelegateBridge __Hotfix0__GetShowFlag; // 0x10
	private static DelegateBridge __Hotfix0__CheckStoryAvailable; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isShow { get; }

	// RVA: 0x274bcf8 VA: 0x7594d63cf8
	public Boolean get_isShow() { }
	// RVA: 0x274bd60 VA: 0x7594d63d60
	public Void UpdateState(Object param) { }
	// RVA: 0x274bde8 VA: 0x7594d63de8
	private Boolean _GetShowFlag() { }
	// RVA: 0x274c140 VA: 0x7594d64140
	private Boolean _CheckStoryAvailable(StoryReviewGroupClientData db) { }
	// RVA: 0x274c230 VA: 0x7594d64230
	public Void .ctor() { }
}
```