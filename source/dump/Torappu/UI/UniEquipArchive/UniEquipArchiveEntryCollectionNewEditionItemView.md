# UniEquipArchiveEntryCollectionNewEditionItemView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Image _imgUniEquipIcon`

- `Image _imgUniEquipTypeIcon`

- `Text _txtUniEquipName`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _uniEquipSingleTypeDesc`

- `Text _uniEquipMultiTypeDesc`

- `Image _uniEquipMultiTypeDescImg`

- `Image _imgShining`

- `Image _imgCharIcon`

- `Text _txtCharName`

- `UIAtlasImage _imgCharColor`

- `GameObject _objCharDetailBtn`

- `Single _charIconNotPhase2Alpha`

- `GameObject _objCharPartClickBtn`

- `Image _imgProfessionIcon`

- `Image _imgSubProfessionIcon`

- `CanvasGroup _canvasNotOwnChar`

- `CanvasGroup _canvasOwnCharNotPhase2`

- `CanvasGroup _canvasOwnCharPhase2UnlockModule`

- `Boolean m_hasInited`

- `String m_cachedUniEquipId`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `FadeSwitchTween m_tweenNotOwnChar`

- `FadeSwitchTween m_tweenOwnCharNotPhase2`

- `FadeSwitchTween m_tweenOwnCharPhase2UnlockModule`


## Methods

- `Void Render(UniEquipArchiveEntryCollectionNewEditionItemViewModel)`

- `Void _InitIfNot()`

- `Builder _GetFadeBuilder(CanvasGroup)`

- `Void OnItemClick()`

- `Void OnCharIconPartClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEntryCollectionNewEditionItemView : MonoBehaviour, IHotfixable
{
	private Image _imgUniEquipIcon; // 0x18
	private Image _imgUniEquipTypeIcon; // 0x20
	private Text _txtUniEquipName; // 0x28
	private GameObject _panelSingleType; // 0x30
	private GameObject _panelMultiType; // 0x38
	private Text _uniEquipSingleTypeDesc; // 0x40
	private Text _uniEquipMultiTypeDesc; // 0x48
	private Image _uniEquipMultiTypeDescImg; // 0x50
	private Image _imgShining; // 0x58
	private Image _imgCharIcon; // 0x60
	private Text _txtCharName; // 0x68
	private UIAtlasImage _imgCharColor; // 0x70
	private GameObject _objCharDetailBtn; // 0x78
	private Single _charIconNotPhase2Alpha; // 0x80
	private GameObject _objCharPartClickBtn; // 0x88
	private Image _imgProfessionIcon; // 0x90
	private Image _imgSubProfessionIcon; // 0x98
	private CanvasGroup _canvasNotOwnChar; // 0xa0
	private CanvasGroup _canvasOwnCharNotPhase2; // 0xa8
	private CanvasGroup _canvasOwnCharPhase2UnlockModule; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private String m_cachedUniEquipId; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd8
	private FadeSwitchTween m_tweenNotOwnChar; // 0xe8
	private FadeSwitchTween m_tweenOwnCharNotPhase2; // 0xf0
	private FadeSwitchTween m_tweenOwnCharPhase2UnlockModule; // 0xf8
	private const Single CHAR_FADE_ALPHA; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__GetFadeBuilder; // 0x10
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x18
	private static DelegateBridge __Hotfix0_OnCharIconPartClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x22edf54 VA: 0x7594905f54
	public Void Render(UniEquipArchiveEntryCollectionNewEditionItemViewModel itemViewModel) { }
	// RVA: 0x22ee44c VA: 0x759490644c
	private Void _InitIfNot() { }
	// RVA: 0x22eeb80 VA: 0x7594906b80
	private Builder _GetFadeBuilder(CanvasGroup canvasGroup) { }
	// RVA: 0x22eec48 VA: 0x7594906c48
	public Void OnItemClick() { }
	// RVA: 0x22eed50 VA: 0x7594906d50
	public Void OnCharIconPartClick() { }
	// RVA: 0x22eee58 VA: 0x7594906e58
	public Void .ctor() { }
}
```