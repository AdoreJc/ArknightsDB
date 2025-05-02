# StageCustomZoneContainerHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Transform _zoneContainerHolder`

- `UIStringEvent _eventMapNotFound`

- `UIStringEvent _eventMapLoadFinish`

- `StageStringClickEvent _stageSelectEvent`

- `UIStringEvent _stageFogUnlockEvent`

- `StageStringClickEvent _specialStageRewardEvent`

- `UIDiffGroupEvent _selectDiffAction`

- `UnityEvent _onDiffSelectDetail`

- `UnityEvent _onAddedReceiveCacheEvent`

- `UnityEvent _onClosePreviewEvent`

- `UIPageFinder m_pageFinder`

- `StageCustomZoneContainer m_zoneContainer`

- `String m_zoneContainerAssetPathCache`


## Methods

- `Void _OnMapNotFound(String)`

- `Void _OnMapLoadFinish(String)`

- `Void _OnStageClicked(String)`

- `Void _OnStageFogClicked(String)`

- `Void _OnSpecialStageRewardClicked(String)`

- `Void _OnSelectDiffAction(StageDiffGroup)`

- `Void _OnDiffSelectDetail()`

- `Void _OnAddedReceiveCacheEvent()`

- `Void _OnClosePreviewEvent()`

- `Void _SetUp(ZoneViewModel)`

- `Void _ClearLoadedContainer()`

- `Void _ClearUpdateCache()`

- `Void _LoadZoneContainer(ZoneViewModel)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageCustomZoneContainerHolder : DataBinder`1
{
	private Transform _zoneContainerHolder; // 0x20
	private UIStringEvent _eventMapNotFound; // 0x28
	private UIStringEvent _eventMapLoadFinish; // 0x30
	private StageStringClickEvent _stageSelectEvent; // 0x38
	private UIStringEvent _stageFogUnlockEvent; // 0x40
	private StageStringClickEvent _specialStageRewardEvent; // 0x48
	private UIDiffGroupEvent _selectDiffAction; // 0x50
	private UnityEvent _onDiffSelectDetail; // 0x58
	private UnityEvent _onAddedReceiveCacheEvent; // 0x60
	private UnityEvent _onClosePreviewEvent; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private StageCustomZoneContainer m_zoneContainer; // 0x80
	private String m_zoneContainerAssetPathCache; // 0x88
	private static DelegateBridge __Hotfix0__OnMapNotFound; // 0x0
	private static DelegateBridge __Hotfix0__OnMapLoadFinish; // 0x8
	private static DelegateBridge __Hotfix0__OnStageClicked; // 0x10
	private static DelegateBridge __Hotfix0__OnStageFogClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnSpecialStageRewardClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnSelectDiffAction; // 0x28
	private static DelegateBridge __Hotfix0__OnDiffSelectDetail; // 0x30
	private static DelegateBridge __Hotfix0__OnAddedReceiveCacheEvent; // 0x38
	private static DelegateBridge __Hotfix0__OnClosePreviewEvent; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x48
	private static DelegateBridge __Hotfix0__SetUp; // 0x50
	private static DelegateBridge __Hotfix0__ClearLoadedContainer; // 0x58
	private static DelegateBridge __Hotfix0__ClearUpdateCache; // 0x60
	private static DelegateBridge __Hotfix0__LoadZoneContainer; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2fa3848 VA: 0x75955bb848
	private Void _OnMapNotFound(String zoneId) { }
	// RVA: 0x2fa38f4 VA: 0x75955bb8f4
	private Void _OnMapLoadFinish(String zoneId) { }
	// RVA: 0x2fa39a0 VA: 0x75955bb9a0
	private Void _OnStageClicked(String stageId) { }
	// RVA: 0x2fa3a4c VA: 0x75955bba4c
	private Void _OnStageFogClicked(String stageId) { }
	// RVA: 0x2fa3af8 VA: 0x75955bbaf8
	private Void _OnSpecialStageRewardClicked(String stageId) { }
	// RVA: 0x2fa3ba4 VA: 0x75955bbba4
	private Void _OnSelectDiffAction(StageDiffGroup diffGroup) { }
	// RVA: 0x2fa3c50 VA: 0x75955bbc50
	private Void _OnDiffSelectDetail() { }
	// RVA: 0x2fa3ccc VA: 0x75955bbccc
	private Void _OnAddedReceiveCacheEvent() { }
	// RVA: 0x2fa3d48 VA: 0x75955bbd48
	private Void _OnClosePreviewEvent() { }
	// RVA: 0x2fa3dc4 VA: 0x75955bbdc4
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fa3fc8 VA: 0x75955bbfc8
	private Void _SetUp(ZoneViewModel model) { }
	// RVA: 0x2fa3edc VA: 0x75955bbedc
	private Void _ClearLoadedContainer() { }
	// RVA: 0x2fa3f58 VA: 0x75955bbf58
	private Void _ClearUpdateCache() { }
	// RVA: 0x2fa40b0 VA: 0x75955bc0b0
	private Void _LoadZoneContainer(ZoneViewModel zoneModel) { }
	// RVA: 0x2fa46ec VA: 0x75955bc6ec
	private Void OnDestroy() { }
	// RVA: 0x2fa4754 VA: 0x75955bc754
	public Void .ctor() { }
}
```