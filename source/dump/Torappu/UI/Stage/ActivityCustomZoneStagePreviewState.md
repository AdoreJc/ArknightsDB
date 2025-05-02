# ActivityCustomZoneStagePreviewState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _previewHolderContainer`

- `ActivityCustomZoneStateBean _stateBean`

- `ActivityCustomZoneStagePreviewHolderBase m_previewHolder`

- `String m_previewPathCache`

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean _TryLoadStagePreviewHolder(String)`

- `Void _ClearLoadedStagePreviewHolder()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneStagePreviewState : PopupFadeState, IValueMsgReceiver
{
	private RectTransform _previewHolderContainer; // 0x70
	private ActivityCustomZoneStateBean _stateBean; // 0x78
	private ActivityCustomZoneStagePreviewHolderBase m_previewHolder; // 0x80
	private String m_previewPathCache; // 0x88
	private UIPageFinder m_pageFinder; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0__TryLoadStagePreviewHolder; // 0x18
	private static DelegateBridge __Hotfix0__ClearLoadedStagePreviewHolder; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2f62f8c VA: 0x759557af8c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f62ff4 VA: 0x759557aff4
	protected override Void OnEnter() { }
	// RVA: 0x2f63400 VA: 0x759557b400
	protected override Void OnExit() { }
	// RVA: 0x2f630d4 VA: 0x759557b0d4
	private Boolean _TryLoadStagePreviewHolder(String prefabPath) { }
	// RVA: 0x2f632f4 VA: 0x759557b2f4
	private Void _ClearLoadedStagePreviewHolder() { }
	// RVA: 0x2f634d8 VA: 0x759557b4d8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2f6355c VA: 0x759557b55c
	public Void .ctor() { }
	// RVA: 0x2f635cc VA: 0x759557b5cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2f635d4 VA: 0x759557b5d4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```