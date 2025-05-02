# CharacterInfoSelectSkillState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSelectSkillBean _stateBean`

- `Tween m_tagTipTweener`


## Methods

- `Void EventOnSkillToggleClick(Int32)`

- `Void EventOnExitSelectSkill()`

- `Void EventOnLvlUp()`

- `Void _OnJumpFromAllLvlUpState(IStateBean)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSelectSkillState : PopupFloatState
{
	private const Single TWEEN_DURATION; // 0x0
	private CharacterInfoSelectSkillBean _stateBean; // 0x70
	private Tween m_tagTipTweener; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_EventOnSkillToggleClick; // 0x10
	private static DelegateBridge __Hotfix0_EventOnExitSelectSkill; // 0x18
	private static DelegateBridge __Hotfix0_EventOnLvlUp; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpFromAllLvlUpState; // 0x28
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x30
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d47f54 VA: 0x759535ff54
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d47fbc VA: 0x759535ffbc
	protected override Void OnResume() { }
	// RVA: 0x2d48030 VA: 0x7595360030
	public Void EventOnSkillToggleClick(Int32 skillIndex) { }
	// RVA: 0x2d48358 VA: 0x7595360358
	public Void EventOnExitSelectSkill() { }
	// RVA: 0x2d483e4 VA: 0x75953603e4
	public Void EventOnLvlUp() { }
	// RVA: 0x2d484fc VA: 0x75953604fc
	private Void _OnJumpFromAllLvlUpState(IStateBean stateBean) { }
	// RVA: 0x2d485a0 VA: 0x75953605a0
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2d48618 VA: 0x7595360618
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2d48790 VA: 0x7595360790
	public Void .ctor() { }
	// RVA: 0x2d48800 VA: 0x7595360800
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d48808 VA: 0x7595360808
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2d48810 VA: 0x7595360810
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```