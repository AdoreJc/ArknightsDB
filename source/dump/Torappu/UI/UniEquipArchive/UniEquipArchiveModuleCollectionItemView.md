# UniEquipArchiveModuleCollectionItemView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Image _imgUniEquipIcon`

- `Image _imgUniEquipTypeIcon`

- `Text _txtUniEquipName`

- `CanvasGroup _objEquipLvPart`

- `UIAtlasObject _atlas`

- `UIAtlasImage _imgUniEquipLevel`

- `CanvasGroup _objEquipCanLvUpPart`

- `CanvasGroup _objEquipLvMaxBgPart`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _uniEquipSingleTypeDesc`

- `Text _uniEquipMultiTypeDesc`

- `Image _uniEquipMultiTypeDescImg`

- `Image _imgShining`

- `Image _imgCharIcon`

- `Text _txtCharName`

- `GameObject _objCharPartClickBtn`

- `CanvasGroup _canvasNotPhase2Part`

- `CanvasGroup _canvasNotUnlockPart`

- `CanvasGroup _objNotUnlockMissionAll`

- `CanvasGroup _objNotUnlockMission1`

- `CanvasGroup _objNotUnlockMission2`

- `CanvasGroup _objNotUnlockMissionAllComplete`

- `CanvasGroup _canvasCanUnlockPart`

- `GameObject _objCanUnlockIconComplete`

- `Boolean m_hasInited`

- `String m_cachedUniEquipId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `FadeSwitchTween m_tweenNotPhase2`

- `FadeSwitchTween m_tweenNotUnlock`

- `FadeSwitchTween m_tweenCanUnlock`

- `Boolean m_canCharCardPartClick`


## Methods

- `Void Render(UniEquipArchiveModuleCollectionItemViewModel)`

- `Void _InitIfNot()`

- `Builder _GetFadeBuilder(CanvasGroup)`

- `Void OnItemClick()`

- `Void OnCharIconPartClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveModuleCollectionItemView : MonoBehaviour, IHotfixable
{
	private Image _imgUniEquipIcon; // 0x18
	private Image _imgUniEquipTypeIcon; // 0x20
	private Text _txtUniEquipName; // 0x28
	private CanvasGroup _objEquipLvPart; // 0x30
	private UIAtlasObject _atlas; // 0x38
	private UIAtlasImage _imgUniEquipLevel; // 0x40
	private CanvasGroup _objEquipCanLvUpPart; // 0x48
	private CanvasGroup _objEquipLvMaxBgPart; // 0x50
	private GameObject _panelSingleType; // 0x58
	private GameObject _panelMultiType; // 0x60
	private Text _uniEquipSingleTypeDesc; // 0x68
	private Text _uniEquipMultiTypeDesc; // 0x70
	private Image _uniEquipMultiTypeDescImg; // 0x78
	private Image _imgShining; // 0x80
	private Image _imgCharIcon; // 0x88
	private Text _txtCharName; // 0x90
	private GameObject _objCharPartClickBtn; // 0x98
	private CanvasGroup _canvasNotPhase2Part; // 0xa0
	private CanvasGroup _canvasNotUnlockPart; // 0xa8
	private CanvasGroup _objNotUnlockMissionAll; // 0xb0
	private CanvasGroup _objNotUnlockMission1; // 0xb8
	private CanvasGroup _objNotUnlockMission2; // 0xc0
	private CanvasGroup _objNotUnlockMissionAllComplete; // 0xc8
	private CanvasGroup _canvasCanUnlockPart; // 0xd0
	private GameObject _objCanUnlockIconComplete; // 0xd8
	private Boolean m_hasInited; // 0xe0
	private String m_cachedUniEquipId; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private UIStateFinder m_stateFinder; // 0x100
	private FadeSwitchTween m_tweenNotPhase2; // 0x110
	private FadeSwitchTween m_tweenNotUnlock; // 0x118
	private FadeSwitchTween m_tweenCanUnlock; // 0x120
	private Boolean m_canCharCardPartClick; // 0x128
	private const String MODULE_LEVEL_PIC_PREFIX; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GetFadeBuilder; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCharIconPartClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22f019c VA: 0x759490819c
	public Void Render(UniEquipArchiveModuleCollectionItemViewModel itemViewModel) { }
	// RVA: 0x22f08a8 VA: 0x75949088a8
	private Void _InitIfNot() { }
	// RVA: 0x22f0fd4 VA: 0x7594908fd4
	private Builder _GetFadeBuilder(CanvasGroup canvasGroup) { }
	// RVA: 0x22f1098 VA: 0x7594909098
	public Void OnItemClick() { }
	// RVA: 0x22f11a0 VA: 0x75949091a0
	public Void OnCharIconPartClick() { }
	// RVA: 0x22f12b0 VA: 0x75949092b0
	public Void .ctor() { }
}
```