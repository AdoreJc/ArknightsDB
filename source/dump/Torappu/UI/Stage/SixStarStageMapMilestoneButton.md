# SixStarStageMapMilestoneButton

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textScore`

- `UICommonTrackPoint _rewardTrackPoint`

- `UIPageFinder m_pageFinder`

- `String m_groupId`

- `TrackPointViewProperty m_rewardTrackProp`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnClickMilestoneButton()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarStageMapMilestoneButton : StageZoneMilestoneButtonBase
{
	private Text _textScore; // 0x18
	private UICommonTrackPoint _rewardTrackPoint; // 0x20
	private UIPageFinder m_pageFinder; // 0x28
	private String m_groupId; // 0x38
	private TrackPointViewProperty m_rewardTrackProp; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0_get_buttonType; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClickMilestoneButton; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override StageZoneMilestoneButtonType buttonType { get; }

	// RVA: 0x2f521ec VA: 0x759556a1ec
	public override StageZoneMilestoneButtonType get_buttonType() { }
	// RVA: 0x2f52254 VA: 0x759556a254
	private Void _InitIfNot() { }
	// RVA: 0x2f522fc VA: 0x759556a2fc
	public override Void Render(ZoneViewModel selectedZoneModel) { }
	// RVA: 0x2f52440 VA: 0x759556a440
	public Void EventOnClickMilestoneButton() { }
	// RVA: 0x2f52540 VA: 0x759556a540
	public Void .ctor() { }
}
```