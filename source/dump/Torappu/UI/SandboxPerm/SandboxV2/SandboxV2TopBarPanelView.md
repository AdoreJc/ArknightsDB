# SandboxV2TopBarPanelView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2TopBarResItemView _goldItemView`

- `SandboxV2TopBarResItemView _moneyItemView`

- `GameObject _pnlButtons`

- `Button _expeditionBtn`

- `Button _eventEffectBtn`

- `Button _logisticsEffectBtn`

- `SandboxV2TopBarFloatPanelView _topBarFloatPanelView`

- `SimpleLayoutContent _secondMatLayout`

- `SandboxV2TopBarSphereView _sphereViewPrefab`

- `Transform _sphereViewContainer`

- `SandboxV2TopBarRiftEffectsView _topBarRiftEffectsView`

- `UIBlendRTImage _bkgBlur`

- `GameObject _bkgColor`

- `SandboxV2TopBarMaterialAdapter m_materialAdapter`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `SandboxV2DungeonViewConfig m_cachedCfg`

- `SandboxV2TopBarSphereView m_sphereView`


## Methods

- `Void Render(SandboxV2DungeonViewModel)`

- `Void _InitIfNot()`

- `Void _RenderButtons(SandboxV2DungeonMiscViewModel)`

- `Void _RenderRiftEffectsView(SandboxV2DungeonMiscViewModel)`

- `Void _RenderPrimaryRes(SandboxV2DungeonMiscViewModel)`

- `Void _RenderSphere(SandboxV2DungeonViewModel)`

- `Void _OnSphereClick()`

- `Void OnBtnDiscardApClicked()`

- `GameObject TutorialOnly_GetSphereBtnGo()`

- `GameObject TutorialOnly_GetCrossDayBtnGo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2TopBarPanelView : MonoBehaviour, IHotfixable
{
	private SandboxV2TopBarResItemView _goldItemView; // 0x18
	private SandboxV2TopBarResItemView _moneyItemView; // 0x20
	private GameObject _pnlButtons; // 0x28
	private Button _expeditionBtn; // 0x30
	private Button _eventEffectBtn; // 0x38
	private Button _logisticsEffectBtn; // 0x40
	private SandboxV2TopBarFloatPanelView _topBarFloatPanelView; // 0x48
	private GameObject[] _split; // 0x50
	private SimpleLayoutContent _secondMatLayout; // 0x58
	private SandboxV2TopBarSphereView _sphereViewPrefab; // 0x60
	private Transform _sphereViewContainer; // 0x68
	private SandboxV2TopBarRiftEffectsView _topBarRiftEffectsView; // 0x70
	private UIBlendRTImage _bkgBlur; // 0x78
	private GameObject _bkgColor; // 0x80
	private SandboxV2TopBarMaterialAdapter m_materialAdapter; // 0x88
	private Boolean m_isInited; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private SandboxV2DungeonViewConfig m_cachedCfg; // 0xa8
	private SandboxV2TopBarSphereView m_sphereView; // 0xb0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RenderButtons; // 0x10
	private static DelegateBridge __Hotfix0__RenderRiftEffectsView; // 0x18
	private static DelegateBridge __Hotfix0__RenderPrimaryRes; // 0x20
	private static DelegateBridge __Hotfix0__RenderSphere; // 0x28
	private static DelegateBridge __Hotfix0__OnSphereClick; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnDiscardApClicked; // 0x38
	private static DelegateBridge __Hotfix0_TutorialOnly_GetSphereBtnGo; // 0x40
	private static DelegateBridge __Hotfix0_TutorialOnly_GetCrossDayBtnGo; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x254cf6c VA: 0x7594b64f6c
	public Void Render(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x254d078 VA: 0x7594b65078
	private Void _InitIfNot() { }
	// RVA: 0x254d350 VA: 0x7594b65350
	private Void _RenderButtons(SandboxV2DungeonMiscViewModel miscViewModel) { }
	// RVA: 0x254d564 VA: 0x7594b65564
	private Void _RenderRiftEffectsView(SandboxV2DungeonMiscViewModel miscViewModel) { }
	// RVA: 0x254d63c VA: 0x7594b6563c
	private Void _RenderPrimaryRes(SandboxV2DungeonMiscViewModel miscViewModel) { }
	// RVA: 0x254d6e4 VA: 0x7594b656e4
	private Void _RenderSphere(SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x254e0b0 VA: 0x7594b660b0
	private Void _OnSphereClick() { }
	// RVA: 0x254e168 VA: 0x7594b66168
	public Void OnBtnDiscardApClicked() { }
	// RVA: 0x254e21c VA: 0x7594b6621c
	public GameObject TutorialOnly_GetSphereBtnGo() { }
	// RVA: 0x254e308 VA: 0x7594b66308
	public GameObject TutorialOnly_GetCrossDayBtnGo() { }
	// RVA: 0x254e3f4 VA: 0x7594b663f4
	public Void .ctor() { }
}
```