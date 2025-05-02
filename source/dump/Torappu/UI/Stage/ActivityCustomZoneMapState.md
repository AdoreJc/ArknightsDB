# ActivityCustomZoneMapState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _mapHolderContainer`

- `ActivityCustomZoneStateBean _stateBean`

- `UnityEvent _onMapBgClicked`

- `String m_zoneMapHolderPathCache`

- `ActivityCustomZoneMapHolderBase m_mapHolder`

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean _TryLoadZoneMapHolder(String)`

- `Void _ClearLoadedZoneMapHolder()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _SelectStage(String)`

- `Void _ClickMapBg()`

- `Void _OpenStagePreview()`

- `Boolean CustomSetActive(Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneMapState : PopupFadeState, IValueMsgReceiver, IPopupCustomActive
{
	public const Int32 ON_SELECT_STAGE; // 0x0
	public const Int32 ON_MAP_BG_CLICK; // 0x0
	private RectTransform _mapHolderContainer; // 0x70
	private ActivityCustomZoneStateBean _stateBean; // 0x78
	private UnityEvent _onMapBgClicked; // 0x80
	private String m_zoneMapHolderPathCache; // 0x88
	private ActivityCustomZoneMapHolderBase m_mapHolder; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__TryLoadZoneMapHolder; // 0x10
	private static DelegateBridge __Hotfix0__ClearLoadedZoneMapHolder; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__SelectStage; // 0x28
	private static DelegateBridge __Hotfix0__ClickMapBg; // 0x30
	private static DelegateBridge __Hotfix0__OpenStagePreview; // 0x38
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2f62570 VA: 0x759557a570
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f625d8 VA: 0x759557a5d8
	protected override Void OnEnter() { }
	// RVA: 0x2f627a0 VA: 0x759557a7a0
	private Boolean _TryLoadZoneMapHolder(String prefabPath) { }
	// RVA: 0x2f629c0 VA: 0x759557a9c0
	private Void _ClearLoadedZoneMapHolder() { }
	// RVA: 0x2f62acc VA: 0x759557aacc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f62b90 VA: 0x759557ab90
	private Void _SelectStage(String stageId) { }
	// RVA: 0x2f62c7c VA: 0x759557ac7c
	private Void _ClickMapBg() { }
	// RVA: 0x2f62d4c VA: 0x759557ad4c
	private Void _OpenStagePreview() { }
	// RVA: 0x2f62e98 VA: 0x759557ae98
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x2f62f14 VA: 0x759557af14
	public Void .ctor() { }
	// RVA: 0x2f62f84 VA: 0x759557af84
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```