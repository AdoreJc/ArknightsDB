# SixStarFogLockStagePlugin

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageFogInfo m_stageFogInfo`

- `StageFogOnButton m_panelFog`

- `UIPageFinder m_pageFinder`


## Methods

- `Boolean _TryHandleMainStageButtonOnMap(StageButtonOnMap)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarFogLockStagePlugin : StageButtonHolderPlugin
{
	private static readonly Color COLOR_BUTTON_MASK; // 0x0
	private StageFogInfo m_stageFogInfo; // 0x28
	private StageFogOnButton m_panelFog; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x18
	private static DelegateBridge __Hotfix0__TryHandleMainStageButtonOnMap; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2f519e8 VA: 0x75955699e8
	protected override Void OnInit() { }
	// RVA: 0x2f51cd4 VA: 0x7595569cd4
	protected override Void OnRenderStage(StageViewModel model) { }
	// RVA: 0x2f51e94 VA: 0x7595569e94
	private Boolean _TryHandleMainStageButtonOnMap(StageButtonOnMap stageButton) { }
	// RVA: 0x2f52004 VA: 0x759556a004
	public Void .ctor() { }
	// RVA: 0x2f52084 VA: 0x759556a084
	private static Void .cctor() { }
}
```