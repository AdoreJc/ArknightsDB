# ActMultiV3MilestoneWidget

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Image _bg`

- `GameObject _isMaxGo`

- `GameObject _lvlTextHolder`

- `Text _lvlNumText`

- `Image _progress`

- `GameObject _progObj`

- `Text _curPointText`

- `Text _maxPointText`

- `RectTransform _mainRewardContent`

- `UIPageFinder m_pageFinder`

- `ActMultiV3MilestoneMainRewardView m_mainRewardView`

- `Boolean m_isInited`


## Methods

- `Void RenderSeason(ActMultiV3MilestoneViewModel)`

- `Void _InitIfNot(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MilestoneWidget : TemplateActivityMilestoneWidget
{
	private const String MAX_FORMAT; // 0x0
	private Image _bg; // 0x18
	private GameObject _isMaxGo; // 0x20
	private GameObject _lvlTextHolder; // 0x28
	private Text _lvlNumText; // 0x30
	private Image _progress; // 0x38
	private GameObject _progObj; // 0x40
	private Text _curPointText; // 0x48
	private Text _maxPointText; // 0x50
	private RectTransform _mainRewardContent; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private ActMultiV3MilestoneMainRewardView m_mainRewardView; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderSeason; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30f6160 VA: 0x759570e160
	public override Void Render(TemplateActivityMilestoneGroupViewModel viewModel) { }
	// RVA: 0x30f6374 VA: 0x759570e374
	public Void RenderSeason(ActMultiV3MilestoneViewModel viewModel) { }
	// RVA: 0x30f6414 VA: 0x759570e414
	private Void _InitIfNot(String actId) { }
	// RVA: 0x30f655c VA: 0x759570e55c
	public Void .ctor() { }
}
```