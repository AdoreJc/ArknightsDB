# Act1ArcadeStageZoneEntryItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `UIAnimationLocation _zoneItemSelectAnim`

- `UIAnimationLocation _zoneItemSelectLightAnim`

- `UIParticle _zoneItemSelectLightPartical`

- `TwoStateToggle _itemStatusTog`

- `Image _imgLock`

- `Image _imgNormal`

- `Text _textUnlockDes`

- `UICommonTrackPoint _trackPoint`

- `Single _zoneItemSelectParticalDelay`

- `TrackPointViewProperty m_trackPointProperty`

- `UIAnimationTween m_zoneItemSelectTween`

- `Builder m_animBuilder`

- `Act1ArcadeStageSelectViewModel m_stageSelectModel`

- `Act1ArcadeSingleZoneModel m_zoneModel`

- `Boolean m_isPrefSelecting`

- `UIStateFinder m_finder`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `UpdateParam m_trackPointParam`


## Properties

- `Boolean m_isSelecting`


## Methods

- `Boolean get_m_isSelecting()`

- `Void _InitIfNot(Act1ArcadeSingleZoneModel)`

- `Void InitView(Act1ArcadeSingleZoneModel, Boolean)`

- `Void _PlaySelectAnim(Builder, Boolean)`

- `IEnumerator _PlayItemSelectLightPartical()`

- `Void EventOnZoneEntryItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageZoneEntryItemView : DataBinder`1
{
	private UIAnimationLocation _zoneItemSelectAnim; // 0x20
	private UIAnimationLocation _zoneItemSelectLightAnim; // 0x30
	private UIParticle _zoneItemSelectLightPartical; // 0x40
	private TwoStateToggle _itemStatusTog; // 0x48
	private Image _imgLock; // 0x50
	private Image _imgNormal; // 0x58
	private Text _textUnlockDes; // 0x60
	private UICommonTrackPoint _trackPoint; // 0x68
	private Single _zoneItemSelectParticalDelay; // 0x70
	private TrackPointViewProperty m_trackPointProperty; // 0x78
	private UIAnimationTween m_zoneItemSelectTween; // 0x80
	private Builder m_animBuilder; // 0x88
	private Act1ArcadeStageSelectViewModel m_stageSelectModel; // 0xb0
	private Act1ArcadeSingleZoneModel m_zoneModel; // 0xb8
	private Boolean m_isPrefSelecting; // 0xc0
	private UIStateFinder m_finder; // 0xc8
	private UIPageFinder m_pageFinder; // 0xd8
	private Boolean m_isInited; // 0xe8
	private UpdateParam m_trackPointParam; // 0xf0
	private static DelegateBridge __Hotfix0_get_m_isSelecting; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_InitView; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__PlaySelectAnim; // 0x20
	private static DelegateBridge __Hotfix0__PlayItemSelectLightPartical; // 0x28
	private static DelegateBridge __Hotfix0_EventOnZoneEntryItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Boolean m_isSelecting { get; }

	// RVA: 0x3416734 VA: 0x7595a2e734
	private Boolean get_m_isSelecting() { }
	// RVA: 0x34167cc VA: 0x7595a2e7cc
	private Void _InitIfNot(Act1ArcadeSingleZoneModel zoneModel) { }
	// RVA: 0x3410d4c VA: 0x7595a28d4c
	public Void InitView(Act1ArcadeSingleZoneModel zoneModel, Boolean isDefaultSelect) { }
	// RVA: 0x3416a14 VA: 0x7595a2ea14
	public override Void OnValueChanged(Act1ArcadeStageSelectProperty property) { }
	// RVA: 0x3416c38 VA: 0x7595a2ec38
	private Void _PlaySelectAnim(Builder animBuilder, Boolean isSelecting) { }
	// RVA: 0x3416df8 VA: 0x7595a2edf8
	private IEnumerator _PlayItemSelectLightPartical() { }
	// RVA: 0x3416ecc VA: 0x7595a2eecc
	public Void EventOnZoneEntryItemClick() { }
	// RVA: 0x3416ff0 VA: 0x7595a2eff0
	public Void .ctor() { }
}
```