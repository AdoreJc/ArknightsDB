# HandBookInfoStageDetailView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `Image _campImage`

- `Transform _illustContainer`

- `Text _charName`

- `Text _charEnglishName`

- `Text _title`

- `Text _detail`

- `TwoStateToggle _finishedToggle`

- `TwoStateToggle _rewardToggle`

- `Text _rewardCountText`

- `Image _imageMapPreview`

- `Image _imageMapTip`

- `GameObject _mapPreview`

- `Image _backTips`

- `Sprite m_stagePreviewMap`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `UICharacterIllust m_illust`

- `Boolean m_isInited`

- `Tween m_enterAnim`

- `UIPageFinder m_pageFinder`


## Methods

- `Void _InitIfNot()`

- `Void OpenMapTips()`

- `Void CloseMapTips()`

- `Void _UnloadStagePreviewMap()`

- `Void _LoadStagePreviewMap(String)`

- `Void _ClearBlurSprite()`

- `Void _ShotBlurredSprite()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookInfoStageDetailView : DataBinder`1
{
	private Image _campImage; // 0x20
	private Transform _illustContainer; // 0x28
	private Text _charName; // 0x30
	private Text _charEnglishName; // 0x38
	private Text _title; // 0x40
	private Text _detail; // 0x48
	private TwoStateToggle _finishedToggle; // 0x50
	private TwoStateToggle _rewardToggle; // 0x58
	private Text _rewardCountText; // 0x60
	private Image _imageMapPreview; // 0x68
	private Image _imageMapTip; // 0x70
	private GameObject _mapPreview; // 0x78
	private Image _backTips; // 0x80
	private Sprite m_stagePreviewMap; // 0x88
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x90
	private UICharacterIllust m_illust; // 0x98
	private Boolean m_isInited; // 0xa0
	private Tween m_enterAnim; // 0xa8
	private UIPageFinder m_pageFinder; // 0xb0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OpenMapTips; // 0x10
	private static DelegateBridge __Hotfix0_CloseMapTips; // 0x18
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0x20
	private static DelegateBridge __Hotfix0__LoadStagePreviewMap; // 0x28
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x30
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2ead2c4 VA: 0x75954c52c4
	private Void _InitIfNot() { }
	// RVA: 0x2ead3d8 VA: 0x75954c53d8
	public override Void OnValueChanged(HandBookInfoStageProperty prop) { }
	// RVA: 0x2ead954 VA: 0x75954c5954
	public Void OpenMapTips() { }
	// RVA: 0x2eadae0 VA: 0x75954c5ae0
	public Void CloseMapTips() { }
	// RVA: 0x2eadcfc VA: 0x75954c5cfc
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x2ead888 VA: 0x75954c5888
	private Void _LoadStagePreviewMap(String stageId) { }
	// RVA: 0x2eadbf8 VA: 0x75954c5bf8
	private Void _ClearBlurSprite() { }
	// RVA: 0x2eada6c VA: 0x75954c5a6c
	private Void _ShotBlurredSprite() { }
	// RVA: 0x2eaddf8 VA: 0x75954c5df8
	private Void OnDestroy() { }
	// RVA: 0x2eade78 VA: 0x75954c5e78
	public Void .ctor() { }
}
```