# StageMixStoryOverallGroupItemProgressPlugin

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `GameObject _stageProgressPanel`

- `GameObject _storyProgressPanel`

- `Text _progressText`

- `UIAnimationLocation _completeAnimation`

- `AnimationWrapper m_completeAnimationWrapper`

- `String m_completeAnimationName`

- `Single m_completeAnimationLength`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupItemProgressPlugin : StageMixStoryOverallGroupItemPlugin
{
	private GameObject _stageProgressPanel; // 0x18
	private GameObject _storyProgressPanel; // 0x20
	private Text _progressText; // 0x28
	private UIAnimationLocation _completeAnimation; // 0x30
	private AnimationWrapper m_completeAnimationWrapper; // 0x40
	private String m_completeAnimationName; // 0x48
	private Single m_completeAnimationLength; // 0x50
	private static DelegateBridge __Hotfix0_get_presentingFeature; // 0x0
	private static DelegateBridge __Hotfix0_IsValid; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override OverallDisplayFeature presentingFeature { get; }

	// RVA: 0x2fea45c VA: 0x759560245c
	public override OverallDisplayFeature get_presentingFeature() { }
	// RVA: 0x2fea4c4 VA: 0x75956024c4
	public override Boolean IsValid(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fea55c VA: 0x759560255c
	public override Void Render(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fea79c VA: 0x759560279c
	public Void .ctor() { }
}
```