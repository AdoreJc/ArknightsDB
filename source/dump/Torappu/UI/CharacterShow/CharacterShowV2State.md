# CharacterShowV2State

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `CharacterShowV2LeftInfoView _leftInfoView`

- `RectTransform _rightInfoContainer`

- `RectTransform _btnBackRt`

- `GameObject _infoHintGo`

- `Text _textInfoHint`

- `ScrollRect _scrollRect`

- `CharacterShowV2StateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSkillClick(String)`

- `Void _OnUniEquipClick(String)`

- `Void _SetEquipScrollRectDragDelegate(CharacterShowBranchView)`

- `Void EventOnBtnBack()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowV2State : State, IValueMsgReceiver
{
	private CharacterShowV2LeftInfoView _leftInfoView; // 0x50
	private CharacterShowRightInfoViewBase[] _rightInfoList; // 0x58
	private RectTransform _rightInfoContainer; // 0x60
	private RectTransform _btnBackRt; // 0x68
	private GameObject _infoHintGo; // 0x70
	private Text _textInfoHint; // 0x78
	private ScrollRect _scrollRect; // 0x80
	public const Int32 MSG_EQUIP_CLICK; // 0x0
	public const Int32 MSG_SKILL_CLICK; // 0x0
	private CharacterShowV2StateBean m_stateBean; // 0x88
	private List`1 m_rightInfoViewList; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0__OnSkillClick; // 0x18
	private static DelegateBridge __Hotfix0__OnUniEquipClick; // 0x20
	private static DelegateBridge __Hotfix0__SetEquipScrollRectDragDelegate; // 0x28
	private static DelegateBridge __Hotfix0_EventOnBtnBack; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2cdf990 VA: 0x75952f7990
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cdf9f8 VA: 0x75952f79f8
	protected override Void OnEnter() { }
	// RVA: 0x2ce048c VA: 0x75952f848c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2ce063c VA: 0x75952f863c
	private Void _OnSkillClick(String skillId) { }
	// RVA: 0x2ce0558 VA: 0x75952f8558
	private Void _OnUniEquipClick(String strVal) { }
	// RVA: 0x2cdfe74 VA: 0x75952f7e74
	private Void _SetEquipScrollRectDragDelegate(CharacterShowBranchView branchView) { }
	// RVA: 0x2ce0948 VA: 0x75952f8948
	public Void EventOnBtnBack() { }
	// RVA: 0x2ce0a14 VA: 0x75952f8a14
	public Void .ctor() { }
	// RVA: 0x2ce0bbc VA: 0x75952f8bbc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```