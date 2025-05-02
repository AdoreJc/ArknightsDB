# StageMixStoryOverallGroupItemTrackPointPlugin

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Transform _trackPointHolder`

- `GameObject m_trackPointInstance`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupItemTrackPointPlugin : StageMixStoryOverallGroupItemPlugin
{
	private Transform _trackPointHolder; // 0x18
	private GameObject m_trackPointInstance; // 0x20
	private static DelegateBridge __Hotfix0_get_presentingFeature; // 0x0
	private static DelegateBridge __Hotfix0_IsValid; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override OverallDisplayFeature presentingFeature { get; }

	// RVA: 0x2fea9f4 VA: 0x75956029f4
	public override OverallDisplayFeature get_presentingFeature() { }
	// RVA: 0x2feaa5c VA: 0x7595602a5c
	public override Boolean IsValid(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2feaaf4 VA: 0x7595602af4
	public override Void Render(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2feac34 VA: 0x7595602c34
	public Void .ctor() { }
}
```