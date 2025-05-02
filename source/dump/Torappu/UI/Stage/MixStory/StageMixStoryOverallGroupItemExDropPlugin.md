# StageMixStoryOverallGroupItemExDropPlugin

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIAtlasImage _exDropColor`

- `String m_cachedExDropGroupId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupItemExDropPlugin : StageMixStoryOverallGroupItemPlugin
{
	private UIAtlasImage _exDropColor; // 0x18
	private String m_cachedExDropGroupId; // 0x20
	private static DelegateBridge __Hotfix0_get_presentingFeature; // 0x0
	private static DelegateBridge __Hotfix0_IsValid; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override OverallDisplayFeature presentingFeature { get; }

	// RVA: 0x2fe9de0 VA: 0x7595601de0
	public override OverallDisplayFeature get_presentingFeature() { }
	// RVA: 0x2fe9e48 VA: 0x7595601e48
	public override Boolean IsValid(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fe9ee4 VA: 0x7595601ee4
	public override Void Render(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fea024 VA: 0x7595602024
	public Void .ctor() { }
}
```