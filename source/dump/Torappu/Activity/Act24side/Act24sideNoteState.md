# Act24sideNoteState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideNoteView _view`

- `RectTransform _backRect`

- `TemplateActivityController m_cacheController`

- `Boolean m_isInited`


## Methods

- `Void BindController(TemplateActivityController)`

- `Void _InitIfNot()`

- `Void OnBackBtnClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideNoteState : PopupFloatState, IBaseActStateHolder, IHotfixable
{
	private Act24sideNoteView _view; // 0x70
	private RectTransform _backRect; // 0x78
	private TemplateActivityController m_cacheController; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_BindController; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnBackBtnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32c01b8 VA: 0x75958d81b8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32c021c VA: 0x75958d821c
	protected override Void OnEnter() { }
	// RVA: 0x32c048c VA: 0x75958d848c
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x32c02f4 VA: 0x75958d82f4
	private Void _InitIfNot() { }
	// RVA: 0x32c0510 VA: 0x75958d8510
	public Void OnBackBtnClick() { }
	// RVA: 0x32c0624 VA: 0x75958d8624
	public Void .ctor() { }
	// RVA: 0x32c0694 VA: 0x75958d8694
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```