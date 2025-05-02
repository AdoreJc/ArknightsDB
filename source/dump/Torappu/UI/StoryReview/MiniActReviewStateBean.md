# MiniActReviewStateBean

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `MiniActTrialProperty m_miniTrialProperty`

- `MiniActDisplayProperty m_displayProperty`

- `TrackPointViewProperty m_newTrialTrackPointProp`

- `TrackPointViewProperty m_collectTrialTrackPointProp`

- `TrackPointViewProperty m_reviewRewardTrackPointProp`


## Properties

- `MiniActTrialProperty miniTrialProp`

- `MiniActDisplayProperty displayProp`

- `TrackPointViewProperty newTrialTrackPointProp`

- `TrackPointViewProperty collectTrialTrackPointProp`

- `TrackPointViewProperty reviewRewardTrackPointProp`


## Methods

- `MiniActTrialProperty get_miniTrialProp()`

- `MiniActDisplayProperty get_displayProp()`

- `TrackPointViewProperty get_newTrialTrackPointProp()`

- `TrackPointViewProperty get_collectTrialTrackPointProp()`

- `TrackPointViewProperty get_reviewRewardTrackPointProp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActReviewStateBean : StoryReviewStateBean
{
	private MiniActTrialProperty m_miniTrialProperty; // 0x18
	private MiniActDisplayProperty m_displayProperty; // 0x20
	private TrackPointViewProperty m_newTrialTrackPointProp; // 0x28
	private TrackPointViewProperty m_collectTrialTrackPointProp; // 0x30
	private TrackPointViewProperty m_reviewRewardTrackPointProp; // 0x38
	private static DelegateBridge __Hotfix0_get_miniTrialProp; // 0x0
	private static DelegateBridge __Hotfix0_get_displayProp; // 0x8
	private static DelegateBridge __Hotfix0_get_newTrialTrackPointProp; // 0x10
	private static DelegateBridge __Hotfix0_get_collectTrialTrackPointProp; // 0x18
	private static DelegateBridge __Hotfix0_get_reviewRewardTrackPointProp; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public MiniActTrialProperty miniTrialProp { get; }
	public MiniActDisplayProperty displayProp { get; }
	public TrackPointViewProperty newTrialTrackPointProp { get; }
	public TrackPointViewProperty collectTrialTrackPointProp { get; }
	public TrackPointViewProperty reviewRewardTrackPointProp { get; }

	// RVA: 0x27594bc VA: 0x7594d714bc
	public MiniActTrialProperty get_miniTrialProp() { }
	// RVA: 0x2759524 VA: 0x7594d71524
	public MiniActDisplayProperty get_displayProp() { }
	// RVA: 0x275958c VA: 0x7594d7158c
	public TrackPointViewProperty get_newTrialTrackPointProp() { }
	// RVA: 0x27595f4 VA: 0x7594d715f4
	public TrackPointViewProperty get_collectTrialTrackPointProp() { }
	// RVA: 0x275965c VA: 0x7594d7165c
	public TrackPointViewProperty get_reviewRewardTrackPointProp() { }
	// RVA: 0x27596c4 VA: 0x7594d716c4
	public Void .ctor() { }
}
```