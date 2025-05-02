# Act1VAutoChessCharSelectState

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `CommonCharSelectResHolder _resHolder`

- `Button _backBtn`

- `TemplateCharSelectController _controller`

- `Act1VAutoChessCharSelectStateBean m_stateBean`

- `Boolean m_inited`


## Properties

- `TemplateCharSelectMainProperty prop`


## Methods

- `TemplateCharSelectMainProperty get_prop()`

- `Void Ensure()`

- `Void _InitIfNot()`

- `Void EventOnReturn()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectState : PopupFadeState, ITemplateCharSelectCtrlHost
{
	private CommonCharSelectResHolder _resHolder; // 0x70
	private Button _backBtn; // 0x78
	private TemplateCharSelectController _controller; // 0x80
	private Act1VAutoChessCharSelectStateBean m_stateBean; // 0x88
	private Boolean m_inited; // 0x90
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_Ensure; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnReturn; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public TemplateCharSelectMainProperty prop { get; }

	// RVA: 0x338da58 VA: 0x75959a5a58
	public TemplateCharSelectMainProperty get_prop() { }
	// RVA: 0x338db30 VA: 0x75959a5b30
	public Void Ensure() { }
	// RVA: 0x338dba4 VA: 0x75959a5ba4
	private Void _InitIfNot() { }
	// RVA: 0x338e04c VA: 0x75959a604c
	public Void EventOnReturn() { }
	// RVA: 0x338e0c0 VA: 0x75959a60c0
	protected override Void OnEnter() { }
	// RVA: 0x338e150 VA: 0x75959a6150
	protected override Void OnResume() { }
	// RVA: 0x338e1d0 VA: 0x75959a61d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x338e238 VA: 0x75959a6238
	public Void .ctor() { }
	// RVA: 0x338e394 VA: 0x75959a6394
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x338e39c VA: 0x75959a639c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```