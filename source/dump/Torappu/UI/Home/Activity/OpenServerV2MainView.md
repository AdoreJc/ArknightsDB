# OpenServerV2MainView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `UIStateFinder m_stateFinder`

- `Int32 m_currentIndex`

- `OpenServerV2MainViewModel m_viewModel`


## Methods

- `Boolean _CheckIndexValid(Int32)`

- `Void _DealWithTabsAvailableOrNot(out)`

- `Void _SelectTab(Int32)`

- `Void _RenderFuncViews(Int32, Boolean)`

- `Int32 _GetIndexByType(OpenServerFuncType)`

- `Void OnBackBtnClick()`

- `Void OnTabBtnClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerV2MainView : OpenServerMainAbstractView
{
	private List`1 _funcList; // 0x18
	private UIStateFinder m_stateFinder; // 0x20
	private Int32 m_currentIndex; // 0x30
	private OpenServerV2MainViewModel m_viewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_UpdateWithType; // 0x8
	private static DelegateBridge __Hotfix0__CheckIndexValid; // 0x10
	private static DelegateBridge __Hotfix0__DealWithTabsAvailableOrNot; // 0x18
	private static DelegateBridge __Hotfix0__SelectTab; // 0x20
	private static DelegateBridge __Hotfix0__RenderFuncViews; // 0x28
	private static DelegateBridge __Hotfix0__GetIndexByType; // 0x30
	private static DelegateBridge __Hotfix0_OnBackBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_OnTabBtnClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x285536c VA: 0x7594e6d36c
	public override Void Render() { }
	// RVA: 0x2855984 VA: 0x7594e6d984
	public override Void UpdateWithType(OpenServerFuncType funcType) { }
	// RVA: 0x2855be8 VA: 0x7594e6dbe8
	private Boolean _CheckIndexValid(Int32 index) { }
	// RVA: 0x28554bc VA: 0x7594e6d4bc
	private Void _DealWithTabsAvailableOrNot(out Int32 firstAvailableIndex) { }
	// RVA: 0x2855674 VA: 0x7594e6d674
	private Void _SelectTab(Int32 index) { }
	// RVA: 0x28557dc VA: 0x7594e6d7dc
	private Void _RenderFuncViews(Int32 index, Boolean isInit) { }
	// RVA: 0x2855adc VA: 0x7594e6dadc
	private Int32 _GetIndexByType(OpenServerFuncType funcType) { }
	// RVA: 0x2855d78 VA: 0x7594e6dd78
	public Void OnBackBtnClick() { }
	// RVA: 0x2855e2c VA: 0x7594e6de2c
	public Void OnTabBtnClick(Int32 index) { }
	// RVA: 0x2855ee0 VA: 0x7594e6dee0
	public Void .ctor() { }
}
```