# ZoneRecordBtnView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UICommonTrackPoint _recordRewardTrack`

- `ZoneRecordBtnContentView _staticContentView`

- `Boolean _isDynamicContent`

- `Transform _dynamicHolder`

- `TrackPointViewProperty m_recordRewardTrack`

- `UIPageFinder m_pageFinder`

- `Boolean m_inited`

- `String m_cacehdDynamicViewId`

- `ZoneRecordBtnContentView m_dynamicView`


## Methods

- `ZoneRecordBtnContentView _EnsureDynamicView(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordBtnView : StageAdditionalBtnView
{
	private UICommonTrackPoint _recordRewardTrack; // 0x18
	private ZoneRecordBtnContentView _staticContentView; // 0x20
	private Boolean _isDynamicContent; // 0x28
	private Transform _dynamicHolder; // 0x30
	private TrackPointViewProperty m_recordRewardTrack; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private Boolean m_inited; // 0x50
	private String m_cacehdDynamicViewId; // 0x58
	private ZoneRecordBtnContentView m_dynamicView; // 0x60
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x0
	private static DelegateBridge __Hotfix0__EnsureDynamicView; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f87a4c VA: 0x759559fa4c
	public override Boolean OnUpdate(ZoneViewModel model) { }
	// RVA: 0x2f87c78 VA: 0x759559fc78
	private ZoneRecordBtnContentView _EnsureDynamicView(String zoneId) { }
	// RVA: 0x2f87bd0 VA: 0x759559fbd0
	private Void _InitIfNot() { }
	// RVA: 0x2f87f2c VA: 0x759559ff2c
	public Void .ctor() { }
}
```