# Act20sideCarVoteEntryState

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Act20sideCarVoteEntryView _entryView`

- `UICommonTrackPoint _leftTimeTrackPoint`

- `Act20sideCarVoteEntryStateBean m_stateBean`

- `Boolean m_isInited`

- `String m_cachedActId`

- `ExhibitionVersus m_cachedVersus`


## Methods

- `Void _OnJumpToCarVote(IStateBean)`

- `Void _OnJumpToCartCompSelect(IStateBean)`

- `Void _InitIfNot()`

- `Void _UpdateProperty()`

- `Void _GoVote()`

- `Boolean _CheckVersus(ExhibitionVersus)`

- `Void EventOnGoVoteClick()`

- `Void EventOnCartDeco()`

- `Void <EventOnGoVoteClick>b__16_0(CarExhibitionJudgeResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarVoteEntryState : PopupFadeState
{
	private Act20sideCarVoteEntryView _entryView; // 0x70
	private UICommonTrackPoint _leftTimeTrackPoint; // 0x78
	private Act20sideCarVoteEntryStateBean m_stateBean; // 0x80
	private Boolean m_isInited; // 0x88
	private String m_cachedActId; // 0x90
	private ExhibitionVersus m_cachedVersus; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToCarVote; // 0x20
	private static DelegateBridge __Hotfix0__OnJumpToCartCompSelect; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__UpdateProperty; // 0x38
	private static DelegateBridge __Hotfix0__GoVote; // 0x40
	private static DelegateBridge __Hotfix0__CheckVersus; // 0x48
	private static DelegateBridge __Hotfix0_EventOnGoVoteClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnCartDeco; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x32f2fcc VA: 0x759590afcc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32f3030 VA: 0x759590b030
	protected override Void OnEnter() { }
	// RVA: 0x32f3394 VA: 0x759590b394
	protected override Void OnResume() { }
	// RVA: 0x32f3408 VA: 0x759590b408
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32f35fc VA: 0x759590b5fc
	private Void _OnJumpToCarVote(IStateBean stateBean) { }
	// RVA: 0x32f3704 VA: 0x759590b704
	private Void _OnJumpToCartCompSelect(IStateBean stateBean) { }
	// RVA: 0x32f30ac VA: 0x759590b0ac
	private Void _InitIfNot() { }
	// RVA: 0x32f3258 VA: 0x759590b258
	private Void _UpdateProperty() { }
	// RVA: 0x32f3fec VA: 0x759590bfec
	private Void _GoVote() { }
	// RVA: 0x32f4168 VA: 0x759590c168
	private Boolean _CheckVersus(ExhibitionVersus versus) { }
	// RVA: 0x32f4264 VA: 0x759590c264
	public Void EventOnGoVoteClick() { }
	// RVA: 0x32f4594 VA: 0x759590c594
	public Void EventOnCartDeco() { }
	// RVA: 0x32f4710 VA: 0x759590c710
	public Void .ctor() { }
	// RVA: 0x32f47bc VA: 0x759590c7bc
	private Void <EventOnGoVoteClick>b__16_0(CarExhibitionJudgeResponse response) { }
	// RVA: 0x32f480c VA: 0x759590c80c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32f4814 VA: 0x759590c814
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x32f481c VA: 0x759590c81c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```