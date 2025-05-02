# CharacterInfoSkillSpecializedState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSelectSkillBean _stateBean`

- `Image _skillLvlImg`

- `Image _skillLvlImgHollow`

- `Tween m_tagTipTweener`

- `RefCountReference m_buildingContextRef`


## Methods

- `Void OnDestroy()`

- `Void _OnPlayerDataChanged(Object)`

- `Void OpenBuildingLevel()`

- `Void EventOnSkillToggleClick(Int32)`

- `Void EventOnLvlUp(Int32)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillSpecializedState : PopupFloatState
{
	private CharacterInfoSelectSkillBean _stateBean; // 0x70
	private Image _skillLvlImg; // 0x78
	private Image _skillLvlImgHollow; // 0x80
	private Tween m_tagTipTweener; // 0x88
	private RefCountReference m_buildingContextRef; // 0x90
	private const Single TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OpenBuildingLevel; // 0x30
	private static DelegateBridge __Hotfix0_EventOnSkillToggleClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnLvlUp; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d4a380 VA: 0x7595362380
	protected override Void OnResume() { }
	// RVA: 0x2d4a4dc VA: 0x75953624dc
	protected override Void OnEnter() { }
	// RVA: 0x2d4a734 VA: 0x7595362734
	protected override Void OnExit() { }
	// RVA: 0x2d4a8b8 VA: 0x75953628b8
	private Void OnDestroy() { }
	// RVA: 0x2d4a438 VA: 0x7595362438
	private Void _OnPlayerDataChanged(Object _object) { }
	// RVA: 0x2d4aab0 VA: 0x7595362ab0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4ab18 VA: 0x7595362b18
	public Void OpenBuildingLevel() { }
	// RVA: 0x2d4ad34 VA: 0x7595362d34
	public Void EventOnSkillToggleClick(Int32 skillIndex) { }
	// RVA: 0x2d4b08c VA: 0x759536308c
	public Void EventOnLvlUp(Int32 index) { }
	// RVA: 0x2d4b220 VA: 0x7595363220
	public Void .ctor() { }
	// RVA: 0x2d4b290 VA: 0x7595363290
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d4b298 VA: 0x7595363298
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d4b2a0 VA: 0x75953632a0
	private Void <>xLuaBaseProxy_OnExit() { }
}
```