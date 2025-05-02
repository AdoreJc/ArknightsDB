# PickerDataSource

**Namespace:** ` `


## Fields

- `RoguelikeTopicChallengeModeViewModel m_model`

- `RoguelikeTopicChallengeCard m_pageViewPrefab`

- `RoguelikeTopicChallengeModelStyle m_style`


## Properties

- `Int32 pageCount`


## Methods

- `Int32 get_pageCount()`

- `IPageView CreatePage(Transform)`

- `Void FlushData(IPageView, Int32)`

- `String GetChallenge(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PickerDataSource : IDataSource, IHotfixable
{
	private RoguelikeTopicChallengeModeViewModel m_model; // 0x10
	private RoguelikeTopicChallengeCard m_pageViewPrefab; // 0x18
	private RoguelikeTopicChallengeModelStyle m_style; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_pageCount; // 0x8
	private static DelegateBridge __Hotfix0_CreatePage; // 0x10
	private static DelegateBridge __Hotfix0_FlushData; // 0x18
	private static DelegateBridge __Hotfix0_GetChallenge; // 0x20

	public Int32 pageCount { get; }

	// RVA: 0x264a360 VA: 0x7594c62360
	public Void .ctor(RoguelikeTopicChallengeModeViewModel model, RoguelikeTopicChallengeCard pageViewPrefab, RoguelikeTopicChallengeModelStyle style) { }
	// RVA: 0x264b6a8 VA: 0x7594c636a8
	public Int32 get_pageCount() { }
	// RVA: 0x264b730 VA: 0x7594c63730
	public IPageView CreatePage(Transform root) { }
	// RVA: 0x264b7f0 VA: 0x7594c637f0
	public Void FlushData(IPageView page, Int32 pageIdx) { }
	// RVA: 0x264b264 VA: 0x7594c63264
	public String GetChallenge(Int32 idx) { }
}
```