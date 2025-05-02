# FifthAnnivExploreSideInfoExpandSubView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _teamNameText`

- `Text _teamCodeText`

- `Text _teamDescText`

- `UIAtlasImage _teamIcon`

- `FifthAnnivExploreValueGroupView _valueGroupView`

- `GameObject _forwardBtnCheckSucc`

- `GameObject _forwardBtnCheckFail`

- `GameObject _normalBtnText`

- `GameObject _checkPointBtnText`

- `Button _forwardBtn`

- `UIAtlasObject _groupIconAtlasObject`

- `UIPageFinder m_pageFinder`

- `FifthAnnivExploreSideInfoViewModel m_cachedViewModel`

- `FifthAnnivExploreValueGroupViewModel m_cachedPrevValueGroupViewModel`


## Methods

- `Void Render(FifthAnnivExploreViewModel)`

- `Void OnForwardBtnClick()`

- `Void OnTargetBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreSideInfoExpandSubView : MonoBehaviour, IHotfixable
{
	private Text _teamNameText; // 0x18
	private Text _teamCodeText; // 0x20
	private Text _teamDescText; // 0x28
	private UIAtlasImage _teamIcon; // 0x30
	private FifthAnnivExploreValueGroupView _valueGroupView; // 0x38
	private GameObject _forwardBtnCheckSucc; // 0x40
	private GameObject _forwardBtnCheckFail; // 0x48
	private GameObject _normalBtnText; // 0x50
	private GameObject _checkPointBtnText; // 0x58
	private Button _forwardBtn; // 0x60
	private UIAtlasObject _groupIconAtlasObject; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private FifthAnnivExploreSideInfoViewModel m_cachedViewModel; // 0x80
	private FifthAnnivExploreValueGroupViewModel m_cachedPrevValueGroupViewModel; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnForwardBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnTargetBtnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x292e150 VA: 0x7594f46150
	public Void Render(FifthAnnivExploreViewModel viewModel) { }
	// RVA: 0x292e330 VA: 0x7594f46330
	public Void OnForwardBtnClick() { }
	// RVA: 0x292e47c VA: 0x7594f4647c
	public Void OnTargetBtnClick() { }
	// RVA: 0x292e530 VA: 0x7594f46530
	public Void .ctor() { }
}
```