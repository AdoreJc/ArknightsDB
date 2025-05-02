# RecruitGachaPoolDetailState

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `RecruitGachaPoolDetailStateBean _stateBean`

- `Transform _holderContainer`

- `GameObject _btnGachaLogGo`

- `RecruitGachaPoolDetailHolder m_holder`

- `Boolean m_isInited`


## Methods

- `Void InitIfNot()`

- `Void SendGetDetailRequest(String, GachaObjGroupType)`

- `Void EventOnBtnRecordClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitGachaPoolDetailState : PopupFloatState
{
	private const String GACHA_LOG_QUERY_KEY; // 0x0
	private RecruitGachaPoolDetailStateBean _stateBean; // 0x70
	private Transform _holderContainer; // 0x78
	private GameObject _btnGachaLogGo; // 0x80
	private RecruitGachaPoolDetailHolder m_holder; // 0x88
	private Boolean m_isInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_SendGetDetailRequest; // 0x18
	private static DelegateBridge __Hotfix0_EventOnBtnRecordClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x26f5d98 VA: 0x7594d0dd98
	public override IStateBean GetCacheBean() { }
	// RVA: 0x26f5e00 VA: 0x7594d0de00
	private Void InitIfNot() { }
	// RVA: 0x26f5f9c VA: 0x7594d0df9c
	protected override Void OnEnter() { }
	// RVA: 0x26f6194 VA: 0x7594d0e194
	private Void SendGetDetailRequest(String gachaPoolId, GachaObjGroupType usingGroupType) { }
	// RVA: 0x26f63ec VA: 0x7594d0e3ec
	public Void EventOnBtnRecordClick() { }
	// RVA: 0x26f66c0 VA: 0x7594d0e6c0
	public Void .ctor() { }
	// RVA: 0x26f6730 VA: 0x7594d0e730
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```