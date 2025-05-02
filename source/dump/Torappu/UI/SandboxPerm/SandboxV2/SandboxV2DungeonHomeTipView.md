# SandboxV2DungeonHomeTipView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imgIcon`

- `UIAtlasImage _imgHomeTip`

- `Text _textBasementLvl`

- `GameObject _pnlEnemyRush`

- `CanvasGroup _alphaHandler`

- `Button _hotspot`

- `UIPageFinder m_pageFinder`

- `String m_cachedCenterNodeId`

- `FadeSwitchTween m_showTween`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _Render(SandboxV2DungeonViewModel)`

- `Void OnBtnClicked()`

- `GameObject TutorialOnly_GetBottomBarHomeBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonHomeTipView : MonoBehaviour, IHotfixable
{
	private const String TEXT_BASEMENT_LVL_FORMAT; // 0x0
	private static readonly SandboxV2ConstructTipType[] CONCERNED_TIPS; // 0x0
	private UIAtlasImage _imgIcon; // 0x18
	private UIAtlasImage _imgHomeTip; // 0x20
	private Text _textBasementLvl; // 0x28
	private GameObject _pnlEnemyRush; // 0x30
	private CanvasGroup _alphaHandler; // 0x38
	private Button _hotspot; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private String m_cachedCenterNodeId; // 0x58
	private FadeSwitchTween m_showTween; // 0x60
	private Boolean m_inited; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_TutorialOnly_GetBottomBarHomeBtnGo; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x255cf10 VA: 0x7594b74f10
	private Void _InitIfNot() { }
	// RVA: 0x255d004 VA: 0x7594b75004
	public Void Render(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x255d0f0 VA: 0x7594b750f0
	private Void _Render(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x255d518 VA: 0x7594b75518
	public Void OnBtnClicked() { }
	// RVA: 0x255d640 VA: 0x7594b75640
	public GameObject TutorialOnly_GetBottomBarHomeBtnGo() { }
	// RVA: 0x255d6c4 VA: 0x7594b756c4
	public Void .ctor() { }
	// RVA: 0x255d744 VA: 0x7594b75744
	private static Void .cctor() { }
}
```