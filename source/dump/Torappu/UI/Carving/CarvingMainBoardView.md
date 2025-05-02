# CarvingMainBoardView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingInputMaterialAreaView _inputMaterialView`

- `CarvingTopInfoView _topInfoView`

- `CarvingMainBoardOutputMaterialView _outputMaterialView`

- `GameObject _goProcessBtnObj`

- `UIAnimationLocation _enterProcessAnimLocation`

- `GameObject _panelInputMat`

- `GameObject _panelOutputMat`

- `GameObject _panelCurrScore`

- `GameObject _panelBtnProcess`

- `GameObject _panelBtnHandbook`

- `Tween m_enterProcessTween`

- `UIPageFinder m_pageFinder`


## Methods

- `Void StateOnlyRegisterTutorialGO()`

- `Void _Render(CarvingMainViewModel)`

- `Void _PlayProcessAnim(CarvingMainViewModel)`

- `Void OnClickProcessBtn()`

- `Void OnClickChallengeInfoBtn()`

- `Void OnClickHandbookBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardView : DataBinder`1
{
	private CarvingInputMaterialAreaView _inputMaterialView; // 0x20
	private CarvingTopInfoView _topInfoView; // 0x28
	private CarvingMainBoardOutputMaterialView _outputMaterialView; // 0x30
	private GameObject _goProcessBtnObj; // 0x38
	private UIAnimationLocation _enterProcessAnimLocation; // 0x40
	private GameObject _panelInputMat; // 0x50
	private GameObject _panelOutputMat; // 0x58
	private GameObject _panelCurrScore; // 0x60
	private GameObject _panelBtnProcess; // 0x68
	private GameObject _panelBtnHandbook; // 0x70
	private Tween m_enterProcessTween; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_StateOnlyRegisterTutorialGO; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__PlayProcessAnim; // 0x18
	private static DelegateBridge __Hotfix0_OnClickProcessBtn; // 0x20
	private static DelegateBridge __Hotfix0_OnClickChallengeInfoBtn; // 0x28
	private static DelegateBridge __Hotfix0_OnClickHandbookBtn; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2d9b9e0 VA: 0x75953b39e0
	public override Void OnValueChanged(CarvingMainProperty property) { }
	// RVA: 0x2d9ac6c VA: 0x75953b2c6c
	public Void StateOnlyRegisterTutorialGO() { }
	// RVA: 0x2d9baa0 VA: 0x75953b3aa0
	private Void _Render(CarvingMainViewModel model) { }
	// RVA: 0x2d9bb90 VA: 0x75953b3b90
	private Void _PlayProcessAnim(CarvingMainViewModel model) { }
	// RVA: 0x2d9be14 VA: 0x75953b3e14
	public Void OnClickProcessBtn() { }
	// RVA: 0x2d9beb8 VA: 0x75953b3eb8
	public Void OnClickChallengeInfoBtn() { }
	// RVA: 0x2d9bf5c VA: 0x75953b3f5c
	public Void OnClickHandbookBtn() { }
	// RVA: 0x2d9c048 VA: 0x75953b4048
	public Void .ctor() { }
}
```