# CommonCharSelectState

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `TemplateCharSelectController _controller`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `RectTransform _rectBackPress`

- `CommonCharSelectStateBean m_stateBean`

- `Boolean m_inited`


## Properties

- `TemplateCharSelectMainProperty prop`


## Methods

- `TemplateCharSelectMainProperty get_prop()`

- `Void Ensure()`

- `Void _InitIfNot()`

- `TemplateCharSelectCardViewModel _CreateCardViewModel(Int32, TemplateCharSelectCharInputData, PlayerCharacter)`

- `Void _SetUpTopMenuHolderInState(Boolean)`

- `Void <_SetUpTopMenuHolderInState>b__13_0(GameObject)`

- `Void <_SetUpTopMenuHolderInState>b__13_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectState : PopupFadeState, ITemplateCharSelectCtrlHost
{
	public TemplateCharSelectController _controller; // 0x70
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x78
	private RectTransform _rectBackPress; // 0x80
	private CommonCharSelectStateBean m_stateBean; // 0x88
	private Boolean m_inited; // 0x90
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_Ensure; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0__CreateCardViewModel; // 0x30
	private static DelegateBridge __Hotfix0__SetUpTopMenuHolderInState; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public TemplateCharSelectMainProperty prop { get; }

	// RVA: 0x2c4f888 VA: 0x7595267888
	public TemplateCharSelectMainProperty get_prop() { }
	// RVA: 0x2c4f960 VA: 0x7595267960
	public Void Ensure() { }
	// RVA: 0x2c4f9d4 VA: 0x75952679d4
	private Void _InitIfNot() { }
	// RVA: 0x2c50408 VA: 0x7595268408
	protected override Void OnEnter() { }
	// RVA: 0x2c50630 VA: 0x7595268630
	protected override Void OnResume() { }
	// RVA: 0x2c506c8 VA: 0x75952686c8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c50730 VA: 0x7595268730
	protected TemplateCharSelectCardViewModel _CreateCardViewModel(Int32 instId, TemplateCharSelectCharInputData inputNullable, PlayerCharacter playerData) { }
	// RVA: 0x2c504bc VA: 0x75952684bc
	protected Void _SetUpTopMenuHolderInState(Boolean hasTopMenuInState) { }
	// RVA: 0x2c50f64 VA: 0x7595268f64
	public Void .ctor() { }
	// RVA: 0x2c51110 VA: 0x7595269110
	private Void <_SetUpTopMenuHolderInState>b__13_0(GameObject instObj) { }
	// RVA: 0x2c511c8 VA: 0x75952691c8
	private Void <_SetUpTopMenuHolderInState>b__13_1() { }
	// RVA: 0x2c511d8 VA: 0x75952691d8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c511e0 VA: 0x75952691e0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```