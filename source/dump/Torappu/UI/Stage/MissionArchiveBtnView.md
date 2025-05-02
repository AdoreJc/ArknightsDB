# MissionArchiveBtnView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UICommonTrackPoint _trackPoint`

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `MissionArchiveDataServiceProxy _proxy`

- `String _topicId`

- `TrackPointViewProperty m_hasRewardTrackProperty`

- `UIPageFinder m_pageFinder`

- `Boolean m_hasInited`

- `MissionArchiveData m_cachedRecordData`

- `Boolean m_cachedEntryOpen`


## Methods

- `Void OnClickEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MissionArchiveBtnView : StageAdditionalBtnView
{
	private UICommonTrackPoint _trackPoint; // 0x18
	private GameObject _normalPanel; // 0x20
	private GameObject _lockedPanel; // 0x28
	private MissionArchiveDataServiceProxy _proxy; // 0x30
	private String _topicId; // 0x38
	private TrackPointViewProperty m_hasRewardTrackProperty; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private Boolean m_hasInited; // 0x58
	private MissionArchiveData m_cachedRecordData; // 0x60
	private Boolean m_cachedEntryOpen; // 0x68
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f8748c VA: 0x759559f48c
	public Void OnClickEvent() { }
	// RVA: 0x2f875dc VA: 0x759559f5dc
	public override Boolean OnUpdate(ZoneViewModel model) { }
	// RVA: 0x2f8773c VA: 0x759559f73c
	private Void _InitIfNot() { }
	// RVA: 0x2f87830 VA: 0x759559f830
	public Void .ctor() { }
}
```