# MedalGroupDisplayState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalDisplayCommonView _view`

- `RectTransform _medalGroupContainer`

- `UIMedalGroupView m_medalGroup`

- `MedalGroupDisplayStateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnDropToMedalPage()`

- `Void _RenderMedalGroup(MedalGroupViewModel)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupDisplayState : PopupFloatState
{
	private MedalDisplayCommonView _view; // 0x70
	private RectTransform _medalGroupContainer; // 0x78
	private UIMedalGroupView m_medalGroup; // 0x80
	private MedalGroupDisplayStateBean m_stateBean; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnDropToMedalPage; // 0x18
	private static DelegateBridge __Hotfix0__RenderMedalGroup; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2796650 VA: 0x7594dae650
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27966b8 VA: 0x7594dae6b8
	private Void _InitIfNot() { }
	// RVA: 0x27967b8 VA: 0x7594dae7b8
	protected override Void OnEnter() { }
	// RVA: 0x2796a4c VA: 0x7594daea4c
	public Void OnDropToMedalPage() { }
	// RVA: 0x2796860 VA: 0x7594dae860
	private Void _RenderMedalGroup(MedalGroupViewModel groupModel) { }
	// RVA: 0x2796bac VA: 0x7594daebac
	public Void .ctor() { }
	// RVA: 0x2796c5c VA: 0x7594daec5c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```