# BuildingStationSelectBuffList

**Namespace:** `Torappu.Building.UI.StationSelect`


## Fields

- `SimpleLayoutContent _buffLayout`

- `RectTransform _panelPadding`

- `RectTransform _panelBound`

- `Boolean m_isInited`

- `BuffAdapter m_buffAdapter`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnEnable()`

- `Void _Init()`

- `IEnumerator _UpdateBuffLayoutCoroutine()`

- `IEnumerator _UpdateEmptyPaddingCoroutine()`

- `Void _OnBuffNextLevelButtonClicked(BuildingBuffDescView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.StationSelect
public class BuildingStationSelectBuffList : DataBinder`1
{
	private SimpleLayoutContent _buffLayout; // 0x20
	private RectTransform _panelPadding; // 0x28
	private RectTransform _panelBound; // 0x30
	private Boolean m_isInited; // 0x38
	private BuffAdapter m_buffAdapter; // 0x40
	private List`1 m_buffList; // 0x48
	private UIPageFinder m_pageFinder; // 0x50
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__Init; // 0x10
	private static DelegateBridge __Hotfix0__UpdateBuffLayoutCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEmptyPaddingCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__OnBuffNextLevelButtonClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x3d98280 VA: 0x75963b0280
	private Void OnEnable() { }
	// RVA: 0x3d983a4 VA: 0x75963b03a4
	public override Void OnValueChanged(StationCharGroupProperty property) { }
	// RVA: 0x3d98548 VA: 0x75963b0548
	private Void _Init() { }
	// RVA: 0x3d982f8 VA: 0x75963b02f8
	private IEnumerator _UpdateBuffLayoutCoroutine() { }
	// RVA: 0x3d985fc VA: 0x75963b05fc
	private IEnumerator _UpdateEmptyPaddingCoroutine() { }
	// RVA: 0x3d9878c VA: 0x75963b078c
	private Void _OnBuffNextLevelButtonClicked(BuildingBuffDescView buffView) { }
	// RVA: 0x3d98a68 VA: 0x75963b0a68
	public Void .ctor() { }
}
```