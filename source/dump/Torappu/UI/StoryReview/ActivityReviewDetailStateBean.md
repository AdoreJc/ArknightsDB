# ActivityReviewDetailStateBean

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TrackPointViewProperty m_newTrialTrackPointProp`

- `TrackPointViewProperty m_collectTrialTrackPointProp`

- `Boolean backToStage`

- `FastExit fastExit`


## Properties

- `TrackPointViewProperty newTrialTrackPointProp`

- `TrackPointViewProperty collectTrialTrackPointProp`


## Methods

- `TrackPointViewProperty get_newTrialTrackPointProp()`

- `TrackPointViewProperty get_collectTrialTrackPointProp()`

- `Void UpdateCollectTrialTrackPoint()`

- `Single CalculatePos(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class ActivityReviewDetailStateBean : IStateBean, IHotfixable
{
	public readonly ActivityReviewDetailProperty entryProp; // 0x10
	private TrackPointViewProperty m_newTrialTrackPointProp; // 0x18
	private TrackPointViewProperty m_collectTrialTrackPointProp; // 0x20
	public Boolean backToStage; // 0x28
	public FastExit fastExit; // 0x2c
	private static DelegateBridge __Hotfix0_get_newTrialTrackPointProp; // 0x0
	private static DelegateBridge __Hotfix0_get_collectTrialTrackPointProp; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCollectTrialTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_CalculatePos; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public TrackPointViewProperty newTrialTrackPointProp { get; }
	public TrackPointViewProperty collectTrialTrackPointProp { get; }

	// RVA: 0x275c848 VA: 0x7594d74848
	public TrackPointViewProperty get_newTrialTrackPointProp() { }
	// RVA: 0x275c8b0 VA: 0x7594d748b0
	public TrackPointViewProperty get_collectTrialTrackPointProp() { }
	// RVA: 0x275c918 VA: 0x7594d74918
	public Void UpdateCollectTrialTrackPoint() { }
	// RVA: 0x275ca8c VA: 0x7594d74a8c
	public Single CalculatePos(String storyTextId) { }
	// RVA: 0x275cbd8 VA: 0x7594d74bd8
	public Void .ctor() { }
}
```