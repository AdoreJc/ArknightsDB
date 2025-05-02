# CrisisV2EntryMainView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasImage _mainBtnBack`

- `Text _mainBtnZoneText`

- `Text _mainBtnTitleText`

- `Text _mainBtnScore`

- `GameObject _noScorePart`

- `GameObject _haveScorePart`

- `GameObject _haveRewardPart`

- `CrisisV2DiagramView _diagramPrefab`

- `RectTransform _diagramContainer`

- `UIAtlasImage _backLeft`

- `UIAtlasImage _backRight`

- `UIAtlasImage _titleImg`

- `Text _remainTime`

- `Text _endingTime`

- `SimpleLayoutContent _tempContent`

- `Image _medalIcon`

- `Text _shopCoin`

- `Text _shopCoinName`

- `CrisisV2EntryTempButtonAdapter m_adapter`

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `CrisisV2DiagramView m_diagram`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _SetGraphicListColor(Graphic[], Color)`

- `Void OnClickMain()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryMainView : DataBinder`1
{
	private UIAtlasImage _mainBtnBack; // 0x20
	private Text _mainBtnZoneText; // 0x28
	private Text _mainBtnTitleText; // 0x30
	private Text _mainBtnScore; // 0x38
	private GameObject _noScorePart; // 0x40
	private GameObject _haveScorePart; // 0x48
	private GameObject _haveRewardPart; // 0x50
	private CrisisV2DiagramView _diagramPrefab; // 0x58
	private RectTransform _diagramContainer; // 0x60
	private UIAtlasImage _backLeft; // 0x68
	private UIAtlasImage _backRight; // 0x70
	private UIAtlasImage _titleImg; // 0x78
	private Text _remainTime; // 0x80
	private Text _endingTime; // 0x88
	private SimpleLayoutContent _tempContent; // 0x90
	private Image _medalIcon; // 0x98
	private Text _shopCoin; // 0xa0
	private Text _shopCoinName; // 0xa8
	private Graphic[] _themeColor1GraphiList; // 0xb0
	private Graphic[] _themeColor2GraphiList; // 0xb8
	private CrisisV2EntryTempButtonAdapter m_adapter; // 0xc0
	private UIPageFinder m_pageFinder; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd8
	private CrisisV2DiagramView m_diagram; // 0xe8
	private Boolean m_isInited; // 0xf0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__SetGraphicListColor; // 0x10
	private static DelegateBridge __Hotfix0_OnClickMain; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bfadf8 VA: 0x7595212df8
	private Void _InitIfNot() { }
	// RVA: 0x2bfafa4 VA: 0x7595212fa4
	public override Void OnValueChanged(CrisisV2EntryProperty property) { }
	// RVA: 0x2bfb6c0 VA: 0x75952136c0
	private Void _SetGraphicListColor(Graphic[] graphicList, Color color) { }
	// RVA: 0x2bfb840 VA: 0x7595213840
	public Void OnClickMain() { }
	// RVA: 0x2bfb8f4 VA: 0x75952138f4
	public Void .ctor() { }
}
```