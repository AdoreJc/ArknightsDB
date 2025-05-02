# UIButtonLink

**Namespace:** `Torappu.UI.ButtonChecker`


## Fields

- `UIPageFinder m_pageFinder`

- `UIStateFinder m_stateFinder`

- `UICompDialogFinder m_dialogFinder`


## Methods

- `Void PlayAudio(AudioModule)`

- `Boolean CheckClickFunc(UIButton)`

- `Boolean _CheckPageAvail(ClickGuardEnum, UIButton)`

- `Boolean _CheckStateAvail(ClickGuardEnum, UIButton)`

- `Boolean _CheckDialogAvail(ClickGuardEnum, UIButton)`

- `Boolean _CheckCommonAvail(ClickGuardEnum, UIButton)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ButtonChecker
public class UIButtonLink : IUIButtonLink, IHotfixable
{
	private UIPageFinder m_pageFinder; // 0x10
	private UIStateFinder m_stateFinder; // 0x20
	private UICompDialogFinder m_dialogFinder; // 0x30
	private static DelegateBridge __Hotfix0_PlayAudio; // 0x0
	private static DelegateBridge __Hotfix0_CheckClickFunc; // 0x8
	private static DelegateBridge __Hotfix0__CheckPageAvail; // 0x10
	private static DelegateBridge __Hotfix0__CheckStateAvail; // 0x18
	private static DelegateBridge __Hotfix0__CheckDialogAvail; // 0x20
	private static DelegateBridge __Hotfix0__CheckCommonAvail; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2c5ed40 VA: 0x7595276d40
	public Void PlayAudio(AudioModule audio) { }
	// RVA: 0x2c5ef0c VA: 0x7595276f0c
	public Boolean CheckClickFunc(UIButton uiButton) { }
	// RVA: 0x2c5f108 VA: 0x7595277108
	private Boolean _CheckPageAvail(ClickGuardEnum detailEnum, UIButton button) { }
	// RVA: 0x2c5f218 VA: 0x7595277218
	private Boolean _CheckStateAvail(ClickGuardEnum detailEnum, UIButton button) { }
	// RVA: 0x2c5f31c VA: 0x759527731c
	private Boolean _CheckDialogAvail(ClickGuardEnum detailEnum, UIButton button) { }
	// RVA: 0x2c5f008 VA: 0x7595277008
	private Boolean _CheckCommonAvail(ClickGuardEnum detailEnum, UIButton button) { }
	// RVA: 0x2c5f420 VA: 0x7595277420
	public Void .ctor() { }
}
```