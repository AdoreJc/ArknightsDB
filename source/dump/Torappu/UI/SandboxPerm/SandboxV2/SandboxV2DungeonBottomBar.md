# SandboxV2DungeonBottomBar

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _pnlShop`

- `GameObject _pnlLogistics`

- `Button _cookPnlBtn`

- `Button _workbenchPnlBtn`

- `SandboxV2DungeonBottomBarFloatPanel _bottomBarFloatPanel`

- `UIBlendRTImage _bkgBlur`

- `UIAtlasImage _imgBkgColor`

- `Single _alphaBkgColor`

- `UIPageFinder m_pageFinder`

- `Boolean m_isInited`

- `SandboxV2DungeonViewModel m_cachedDungeonViewModel`


## Methods

- `Void _InitIfNot()`

- `Void Render(SandboxV2DungeonViewModel)`

- `Void OnBtnOtherClicked()`

- `GameObject TutorialOnly_GetCookPanelBtnGo()`

- `GameObject TutorialOnly_GetWorkbenchPanelBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonBottomBar : MonoBehaviour, IHotfixable
{
	private GameObject _pnlShop; // 0x18
	private GameObject _pnlLogistics; // 0x20
	private Button _cookPnlBtn; // 0x28
	private Button _workbenchPnlBtn; // 0x30
	private SandboxV2DungeonBottomBarFloatPanel _bottomBarFloatPanel; // 0x38
	private UIBlendRTImage _bkgBlur; // 0x40
	private UIAtlasImage _imgBkgColor; // 0x48
	private Single _alphaBkgColor; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private Boolean m_isInited; // 0x68
	private SandboxV2DungeonViewModel m_cachedDungeonViewModel; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnOtherClicked; // 0x10
	private static DelegateBridge __Hotfix0_TutorialOnly_GetCookPanelBtnGo; // 0x18
	private static DelegateBridge __Hotfix0_TutorialOnly_GetWorkbenchPanelBtnGo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x255c42c VA: 0x7594b7442c
	private Void _InitIfNot() { }
	// RVA: 0x255c568 VA: 0x7594b74568
	public Void Render(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x255c63c VA: 0x7594b7463c
	public Void OnBtnOtherClicked() { }
	// RVA: 0x255ca00 VA: 0x7594b74a00
	public GameObject TutorialOnly_GetCookPanelBtnGo() { }
	// RVA: 0x255ca74 VA: 0x7594b74a74
	public GameObject TutorialOnly_GetWorkbenchPanelBtnGo() { }
	// RVA: 0x255cae8 VA: 0x7594b74ae8
	public Void .ctor() { }
}
```