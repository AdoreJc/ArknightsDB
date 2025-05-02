# SandboxV2DungeonSphereRiftView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _txtMainTitle`

- `Text _txtSubTitle`

- `Text _txtRemainDay`

- `GameObject _objDirectLeaveBtnFinish`

- `GameObject _objDirectLeaveBtnUnFinish`

- `GameObject _objMainMissionFinish`

- `Text _txtMainMissionFinish`

- `GameObject _objMainMissionFail`

- `Text _txtMainMissionFail`

- `GameObject _objMainMissionUnFinish`

- `Text _txtMainMissionUnFinish`

- `Text _seasonName`

- `Text _seasonDesc`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void OnBtnDirectLeaveClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonSphereRiftView : MonoBehaviour, IHotfixable
{
	private Text _txtMainTitle; // 0x18
	private Text _txtSubTitle; // 0x20
	private Text _txtRemainDay; // 0x28
	private GameObject _objDirectLeaveBtnFinish; // 0x30
	private GameObject _objDirectLeaveBtnUnFinish; // 0x38
	private GameObject _objMainMissionFinish; // 0x40
	private Text _txtMainMissionFinish; // 0x48
	private GameObject _objMainMissionFail; // 0x50
	private Text _txtMainMissionFail; // 0x58
	private GameObject _objMainMissionUnFinish; // 0x60
	private Text _txtMainMissionUnFinish; // 0x68
	private Text _seasonName; // 0x70
	private Text _seasonDesc; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnBtnDirectLeaveClicked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2550a84 VA: 0x7594b68a84
	public Void Render(SandboxV2DungeonViewModel viewModel) { }
	// RVA: 0x25518c8 VA: 0x7594b698c8
	public Void OnBtnDirectLeaveClicked() { }
	// RVA: 0x255197c VA: 0x7594b6997c
	public Void .ctor() { }
}
```