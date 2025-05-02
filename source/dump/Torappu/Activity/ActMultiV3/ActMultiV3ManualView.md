# ActMultiV3ManualView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `UIStyleProvider _styleProvider`

- `Image _seasonLogo`

- `ActMultiV3ProfileView _profileView`

- `UIPageFinder m_pageFinder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualView : DataBinder`1, IHotfixable
{
	private UIStyleProvider _styleProvider; // 0x20
	private Image _seasonLogo; // 0x28
	private ActMultiV3ProfileView _profileView; // 0x30
	private ActMultiV3ManualTabView[] _tabViews; // 0x38
	private UIPageFinder m_pageFinder; // 0x40
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30fc5d0 VA: 0x75957145d0
	public override Void OnValueChanged(ActMultiV3ManualProperty property) { }
	// RVA: 0x30fcb38 VA: 0x7595714b38
	public Void .ctor() { }
}
```