# MedalEntryState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalEntryListBtn _listBtn`

- `RectTransform _diyContainer`

- `RectTransform _groupContainer`

- `MedalListStateBean _stateBean`

- `UIMedalGroupView m_diyMedalGroup`

- `UIMedalGroupView m_actMedalGroup`

- `Boolean _initIfNot`


## Methods

- `Void OnClickList()`

- `Void OnClickGroup()`

- `Void OnClickSelect()`

- `Void OnDIYClicked()`

- `Void _LoadDIYMedalGroup()`

- `Void _LoadActMedalGroup()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalEntryState : State
{
	private MedalEntryListBtn _listBtn; // 0x50
	private RectTransform _diyContainer; // 0x58
	private RectTransform _groupContainer; // 0x60
	private MedalListStateBean _stateBean; // 0x68
	private UIMedalGroupView m_diyMedalGroup; // 0x70
	private UIMedalGroupView m_actMedalGroup; // 0x78
	private Boolean _initIfNot; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnClickList; // 0x18
	private static DelegateBridge __Hotfix0_OnClickGroup; // 0x20
	private static DelegateBridge __Hotfix0_OnClickSelect; // 0x28
	private static DelegateBridge __Hotfix0_OnDIYClicked; // 0x30
	private static DelegateBridge __Hotfix0__LoadDIYMedalGroup; // 0x38
	private static DelegateBridge __Hotfix0__LoadActMedalGroup; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x27958dc VA: 0x7594dad8dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2795944 VA: 0x7594dad944
	protected override Void OnEnter() { }
	// RVA: 0x27960e4 VA: 0x7594dae0e4
	protected override Void OnResume() { }
	// RVA: 0x27961b8 VA: 0x7594dae1b8
	public Void OnClickList() { }
	// RVA: 0x2796320 VA: 0x7594dae320
	public Void OnClickGroup() { }
	// RVA: 0x279642c VA: 0x7594dae42c
	public Void OnClickSelect() { }
	// RVA: 0x2796538 VA: 0x7594dae538
	public Void OnDIYClicked() { }
	// RVA: 0x2795b30 VA: 0x7594dadb30
	private Void _LoadDIYMedalGroup() { }
	// RVA: 0x2795ec4 VA: 0x7594dadec4
	private Void _LoadActMedalGroup() { }
	// RVA: 0x27965d0 VA: 0x7594dae5d0
	public Void .ctor() { }
	// RVA: 0x2796640 VA: 0x7594dae640
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2796648 VA: 0x7594dae648
	private Void <>xLuaBaseProxy_OnResume() { }
}
```