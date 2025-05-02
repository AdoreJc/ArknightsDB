# RecruitPage

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Transform _originTransform`

- `PrefabInstHolder _topMenuHolder`

- `RecruitStateBean _stateBean`

- `Action m_stateSwitchCallback`

- `Vector2 m_fromContentPos`

- `RefCountReference m_buildingContextRef`


## Methods

- `Void Start()`

- `Void ShowGachaEffect(GachaResult, Boolean, Boolean)`

- `Void ShowTenGachaEffect(GachaResult[], Boolean, Boolean)`

- `Void _ShowError(Boolean)`

- `Void _OnInitTopMenu(GameObject)`

- `Void _UpdateStatusWhenBackToRecruit(Param, UIPageTransContext)`

- `Void <ShowTenGachaEffect>b__13_0(Output)`

- `Void <_OnInitTopMenu>b__15_0()`

- `Void <_OnInitTopMenu>b__15_1(UIRouteTarget, Object, Action`2)`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitPage : StateEnginePage
{
	private Transform _originTransform; // 0xe8
	private PrefabInstHolder _topMenuHolder; // 0xf0
	private RecruitStateBean _stateBean; // 0xf8
	private Action m_stateSwitchCallback; // 0x100
	private Vector2 m_fromContentPos; // 0x108
	private RefCountReference m_buildingContextRef; // 0x110
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x18
	private static DelegateBridge __Hotfix0_ShowGachaEffect; // 0x20
	private static DelegateBridge __Hotfix0_ShowTenGachaEffect; // 0x28
	private static DelegateBridge __Hotfix0__ShowError; // 0x30
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x38
	private static DelegateBridge __Hotfix0__UpdateStatusWhenBackToRecruit; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override AVGPageKey avgPage { get; }

	// RVA: 0x26f2628 VA: 0x7594d0a628
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x26f2690 VA: 0x7594d0a690
	private Void Start() { }
	// RVA: 0x26f2754 VA: 0x7594d0a754
	protected override Void OnStart() { }
	// RVA: 0x26f297c VA: 0x7594d0a97c
	protected override Void OnPageRouted() { }
	// RVA: 0x26f2a60 VA: 0x7594d0aa60
	public Void ShowGachaEffect(GachaResult gachaResult, Boolean isAdvanced, Boolean isSkippable) { }
	// RVA: 0x26f2f00 VA: 0x7594d0af00
	public Void ShowTenGachaEffect(GachaResult[] gachaResultList, Boolean isAdvanced, Boolean isSkippable) { }
	// RVA: 0x26f2e14 VA: 0x7594d0ae14
	private Void _ShowError(Boolean isAdvanced) { }
	// RVA: 0x26f3390 VA: 0x7594d0b390
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x26f28a4 VA: 0x7594d0a8a4
	private Void _UpdateStatusWhenBackToRecruit(Param param, UIPageTransContext transContext) { }
	// RVA: 0x26f3530 VA: 0x7594d0b530
	public Void .ctor() { }
	// RVA: 0x26f35a0 VA: 0x7594d0b5a0
	private Void <ShowTenGachaEffect>b__13_0(Output output) { }
	// RVA: 0x26f363c VA: 0x7594d0b63c
	private Void <_OnInitTopMenu>b__15_0() { }
	// RVA: 0x26f3690 VA: 0x7594d0b690
	private Void <_OnInitTopMenu>b__15_1(UIRouteTarget target, Object param, Action`2 baseHandler) { }
	// RVA: 0x26f3834 VA: 0x7594d0b834
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x26f383c VA: 0x7594d0b83c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x26f3844 VA: 0x7594d0b844
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```