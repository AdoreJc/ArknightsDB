# NameCardV2View

**Namespace:** `Torappu.UI.Friend`


## Fields

- `RectTransform _selectedModuleContainer`

- `Transform _avatarViewContainer`

- `Transform _detailViewContainer`

- `Transform _simpleViewContainer`

- `Transform _bgViewContainer`

- `Transform _collectViewContainer`

- `Transform _illustViewContainer`

- `UIStyleProvider _styleProvider`

- `UIAnimationLocation _switchDetailAnim`

- `Single _duration`

- `Transform m_scaleHost`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_cachedEditSeqNum`

- `Int32 m_cachedShowDetailSeqNum`

- `AnimationSwitchTween m_tween`

- `CrossAppShareStartLayoutContent _shareBackgroundContent`

- `CrossAppShareStartLayoutContent _shareIllustContent`

- `CrossAppShareStartLayoutContent _shareCollectContent`

- `CrossAppShareStartLayoutContent _shareAvatarContent`

- `CrossAppShareStartLayoutContent _shareSimpleAvatarContent`

- `CrossAppShareStartLayoutContent _shareRemovableContent`


## Methods

- `Boolean IsTweening()`

- `Transform GetScaleHost()`

- `Void SetScaleHost(Transform)`

- `Void _InitIfNot()`

- `Void _ReloadModuleObjects(List`1)`

- `Void _RenderAndSortSelectedModules(List`1)`

- `Void _RenderAndSortSelectedModulesWithTween(ListDict`2)`

- `Void _OnModuleHidden(String)`

- `Transform _GetFixedModuleContainer(NameCardV2ModuleType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2View : DataBinder`1
{
	private RectTransform _selectedModuleContainer; // 0x20
	private Transform _avatarViewContainer; // 0x28
	private Transform _detailViewContainer; // 0x30
	private Transform _simpleViewContainer; // 0x38
	private Transform _bgViewContainer; // 0x40
	private Transform _collectViewContainer; // 0x48
	private Transform _illustViewContainer; // 0x50
	private UIStyleProvider _styleProvider; // 0x58
	private UIAnimationLocation _switchDetailAnim; // 0x60
	private Single _duration; // 0x70
	private Transform m_scaleHost; // 0x78
	private ListDict`2 m_fixedModules; // 0x80
	private ListDict`2 m_selectedModules; // 0x88
	private Boolean m_hasInited; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private Int32 m_cachedEditSeqNum; // 0xa8
	private Int32 m_cachedShowDetailSeqNum; // 0xac
	private AnimationSwitchTween m_tween; // 0xb0
	private CrossAppShareStartLayoutContent _shareBackgroundContent; // 0xb8
	private CrossAppShareStartLayoutContent _shareIllustContent; // 0xc0
	private CrossAppShareStartLayoutContent _shareCollectContent; // 0xc8
	private CrossAppShareStartLayoutContent _shareAvatarContent; // 0xd0
	private CrossAppShareStartLayoutContent _shareSimpleAvatarContent; // 0xd8
	private CrossAppShareStartLayoutContent _shareRemovableContent; // 0xe0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_IsTweening; // 0x8
	private static DelegateBridge __Hotfix0_GetScaleHost; // 0x10
	private static DelegateBridge __Hotfix0_SetScaleHost; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ReloadModuleObjects; // 0x28
	private static DelegateBridge __Hotfix0__RenderAndSortSelectedModules; // 0x30
	private static DelegateBridge __Hotfix0__RenderAndSortSelectedModulesWithTween; // 0x38
	private static DelegateBridge __Hotfix0__OnModuleHidden; // 0x40
	private static DelegateBridge __Hotfix0__GetFixedModuleContainer; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x28e81e8 VA: 0x7594f001e8
	public override Void OnValueChanged(NameCardV2Property property) { }
	// RVA: 0x28e9554 VA: 0x7594f01554
	public Boolean IsTweening() { }
	// RVA: 0x28de2ec VA: 0x7594ef62ec
	public Transform GetScaleHost() { }
	// RVA: 0x28e95d0 VA: 0x7594f015d0
	public Void SetScaleHost(Transform scaleHost) { }
	// RVA: 0x28e8888 VA: 0x7594f00888
	private Void _InitIfNot() { }
	// RVA: 0x28e8ac4 VA: 0x7594f00ac4
	private Void _ReloadModuleObjects(List`1 selectedModuleIds) { }
	// RVA: 0x28e8ddc VA: 0x7594f00ddc
	private Void _RenderAndSortSelectedModules(List`1 models) { }
	// RVA: 0x28e8f44 VA: 0x7594f00f44
	private Void _RenderAndSortSelectedModulesWithTween(ListDict`2 listDict) { }
	// RVA: 0x28e965c VA: 0x7594f0165c
	private Void _OnModuleHidden(String moduleId) { }
	// RVA: 0x28e8a04 VA: 0x7594f00a04
	private Transform _GetFixedModuleContainer(NameCardV2ModuleType type) { }
	// RVA: 0x28e9774 VA: 0x7594f01774
	public Void .ctor() { }
}
```