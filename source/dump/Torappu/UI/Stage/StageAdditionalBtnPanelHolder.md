# StageAdditionalBtnPanelHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `UIPageFinder m_pageFinder`

- `String m_cachedPanelId`

- `StageAdditionalBtnPanel m_panel`


## Methods

- `StageAdditionalBtnPanel _EnsurePanel(ZoneData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageAdditionalBtnPanelHolder : DataBinder`1
{
	private UIPageFinder m_pageFinder; // 0x20
	private String m_cachedPanelId; // 0x30
	private StageAdditionalBtnPanel m_panel; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__EnsurePanel; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f9fe30 VA: 0x75955b7e30
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2f9ff2c VA: 0x75955b7f2c
	private StageAdditionalBtnPanel _EnsurePanel(ZoneData zoneData) { }
	// RVA: 0x2fa0208 VA: 0x75955b8208
	public Void .ctor() { }
}
```