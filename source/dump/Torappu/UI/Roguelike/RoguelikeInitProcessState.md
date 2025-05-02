# RoguelikeInitProcessState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIStyleProvider _styleProvider`

- `RoguelikeInitStyle m_style`

- `RoguelikeInitModelProperty m_property`

- `PlayerRoguelikePlayerEventType m_cachedInitPhase`

- `MenuAdapter m_menuAdapter`

- `Boolean m_showStatusBar`

- `Boolean m_showBottomBar`


## Properties

- `String topicId`

- `UIPage page`


## Methods

- `Void _InitIfNot()`

- `Void _ExitInitProcess()`

- `String get_topicId()`

- `UIPage get_page()`

- `Void Invalide()`

- `Boolean AddTop()`

- `Void <RegisterToDataListener>b__12_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeInitProcessState : PopupFadeState, RoguelikeInitContextUser, IHotfixable
{
	private RoguelikeInitPanel[] _panels; // 0x70
	private UIStyleProvider _styleProvider; // 0x78
	private RoguelikeInitStyle m_style; // 0x80
	private RoguelikeInitModelProperty m_property; // 0x88
	private PlayerRoguelikePlayerEventType m_cachedInitPhase; // 0x90
	private MenuAdapter m_menuAdapter; // 0x98
	private Boolean m_showStatusBar; // 0xa0
	private Boolean m_showBottomBar; // 0xa1
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ExitInitProcess; // 0x28
	private static DelegateBridge __Hotfix0_get_topicId; // 0x30
	private static DelegateBridge __Hotfix0_get_page; // 0x38
	private static DelegateBridge __Hotfix0_Invalide; // 0x40
	private static DelegateBridge __Hotfix0_AddTop; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String topicId { get; }
	public UIPage page { get; }

	// RVA: 0x2a3c480 VA: 0x7595054480
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a3c4e4 VA: 0x75950544e4
	protected override Void OnEnter() { }
	// RVA: 0x2a3cac8 VA: 0x7595054ac8
	protected override Void OnResume() { }
	// RVA: 0x2a3cbf8 VA: 0x7595054bf8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2a3c65c VA: 0x759505465c
	private Void _InitIfNot() { }
	// RVA: 0x2a3ce00 VA: 0x7595054e00
	private Void _ExitInitProcess() { }
	// RVA: 0x2a3cd70 VA: 0x7595054d70
	public String get_topicId() { }
	// RVA: 0x2a3cf90 VA: 0x7595054f90
	public UIPage get_page() { }
	// RVA: 0x2a3c978 VA: 0x7595054978
	public Void Invalide() { }
	// RVA: 0x VA: 0x0
	public Boolean AddTop() { }
	// RVA: 0x2a3cffc VA: 0x7595054ffc
	public Void .ctor() { }
	// RVA: 0x2a3d074 VA: 0x7595055074
	private Void <RegisterToDataListener>b__12_0(IStateBean stateBean) { }
	// RVA: 0x2a3d1cc VA: 0x75950551cc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a3d1d4 VA: 0x75950551d4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a3d1dc VA: 0x75950551dc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```