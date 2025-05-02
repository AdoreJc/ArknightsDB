# Act38sideFireworkSquadPluginView

**Namespace:** `Torappu.Activity.Act38side`


## Fields

- `GameObject _panelSelf`

- `Image _imgAnimBkg`

- `SimpleLayoutContent _content`

- `RectTransform _plateContainer`

- `GameObject _panelEditBtn`

- `UIColorGraphic _buttonTarget`

- `Act38sideFireworkSquadPluginViewModel m_viewModel`

- `Boolean m_hasInited`

- `String m_cachedAnimalId`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`

- `FireworkPlateView m_plateView`

- `FireworkPlateViewStyle m_style`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnEditBtnClicked()`

- `Void _InitIfNot()`

- `Void _Render()`

- `Void _EventOnAnimalClicked(String)`

- `Void _OnAnimalChangeProceed(FireworkChangeAnimalResponse)`

- `Void _TryTriggerTutorialAVG()`

- `Void _OnTutorialAVGCompleted(String, Boolean)`

- `Void _ShowGuideBookTrigger(Story)`

- `Void _RegisterTutorialGameObject()`

- `Void <_TryTriggerTutorialAVG>b__23_0(Story)`

- `Void <_TryTriggerTutorialAVG>b__23_1(Story)`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act38side
public class Act38sideFireworkSquadPluginView : SquadHomePluginView, IHotfixable
{
	private const String GUIDE_SUB_SIGNAL; // 0x0
	private GameObject _panelSelf; // 0x30
	private Image _imgAnimBkg; // 0x38
	private SimpleLayoutContent _content; // 0x40
	private RectTransform _plateContainer; // 0x48
	private GameObject _panelEditBtn; // 0x50
	private UIColorGraphic _buttonTarget; // 0x58
	private Act38sideFireworkSquadPluginViewModel m_viewModel; // 0x60
	private Boolean m_hasInited; // 0x68
	private String m_cachedAnimalId; // 0x70
	private Adapter m_adapter; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private FireworkPlateView m_plateView; // 0x90
	private FireworkPlateViewStyle m_style; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x8
	private static DelegateBridge __Hotfix0_EventOnEditBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0__EventOnAnimalClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnAnimalChangeProceed; // 0x30
	private static DelegateBridge __Hotfix0__TryTriggerTutorialAVG; // 0x38
	private static DelegateBridge __Hotfix0__OnTutorialAVGCompleted; // 0x40
	private static DelegateBridge __Hotfix0__ShowGuideBookTrigger; // 0x48
	private static DelegateBridge __Hotfix0__RegisterTutorialGameObject; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x323ed28 VA: 0x7595856d28
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x323fc28 VA: 0x7595857c28
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x323fc8c VA: 0x7595857c8c
	public Void EventOnEditBtnClicked() { }
	// RVA: 0x323eddc VA: 0x7595856ddc
	private Void _InitIfNot() { }
	// RVA: 0x323fa28 VA: 0x7595857a28
	private Void _Render() { }
	// RVA: 0x323fe9c VA: 0x7595857e9c
	private Void _EventOnAnimalClicked(String animId) { }
	// RVA: 0x32401ac VA: 0x75958581ac
	private Void _OnAnimalChangeProceed(FireworkChangeAnimalResponse response) { }
	// RVA: 0x323f0a0 VA: 0x75958570a0
	private Void _TryTriggerTutorialAVG() { }
	// RVA: 0x32402fc VA: 0x75958582fc
	private Void _OnTutorialAVGCompleted(String customOperationKey, Boolean showGuidebookTrigger) { }
	// RVA: 0x324044c VA: 0x759585844c
	private Void _ShowGuideBookTrigger(Story story) { }
	// RVA: 0x323f24c VA: 0x759585724c
	private Void _RegisterTutorialGameObject() { }
	// RVA: 0x32404e8 VA: 0x75958584e8
	public Void .ctor() { }
	// RVA: 0x32406e4 VA: 0x75958586e4
	private Void <_TryTriggerTutorialAVG>b__23_0(Story story) { }
	// RVA: 0x3240730 VA: 0x7595858730
	private Void <_TryTriggerTutorialAVG>b__23_1(Story story) { }
	// RVA: 0x324077c VA: 0x759585877c
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
}
```