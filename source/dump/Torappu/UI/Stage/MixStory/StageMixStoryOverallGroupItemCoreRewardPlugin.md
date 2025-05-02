# StageMixStoryOverallGroupItemCoreRewardPlugin

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `Transform _coreRewardContainer`

- `Single _coreRewardItemScale`

- `Text _coreRewardNameText`

- `Color _unclaimedTextColor`

- `Color _claimedTextColor`

- `UIColorGroupSetter _colorSetter`

- `Color _unclaimedSetColor`

- `Color _claimedSetColor`

- `GameObject _unclaimedPanel`

- `GameObject _claimedPanel`

- `UIItemCard m_coreRewardItemCard`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallGroupItemCoreRewardPlugin : StageMixStoryOverallGroupItemPlugin
{
	private Transform _coreRewardContainer; // 0x18
	private Single _coreRewardItemScale; // 0x20
	private Text _coreRewardNameText; // 0x28
	private Color _unclaimedTextColor; // 0x30
	private Color _claimedTextColor; // 0x40
	private UIColorGroupSetter _colorSetter; // 0x50
	private Color _unclaimedSetColor; // 0x58
	private Color _claimedSetColor; // 0x68
	private GameObject _unclaimedPanel; // 0x78
	private GameObject _claimedPanel; // 0x80
	private UIItemCard m_coreRewardItemCard; // 0x88
	private static DelegateBridge __Hotfix0_get_presentingFeature; // 0x0
	private static DelegateBridge __Hotfix0_IsValid; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override OverallDisplayFeature presentingFeature { get; }

	// RVA: 0x2fe9858 VA: 0x7595601858
	public override OverallDisplayFeature get_presentingFeature() { }
	// RVA: 0x2fe98c0 VA: 0x75956018c0
	public override Boolean IsValid(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fe995c VA: 0x759560195c
	public override Void Render(StageStorylineStorySetViewModel model) { }
	// RVA: 0x2fe9b10 VA: 0x7595601b10
	private Void _InitIfNot() { }
	// RVA: 0x2fe9cf8 VA: 0x7595601cf8
	public Void .ctor() { }
}
```