# Act3D0GachaBoxState

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Act3D0GachaBoxStateBean _stateBean`

- `Act3D0GachaBoxRightPartView _rightPartView`

- `Act3D0ClueShowPart _showPart`

- `GameObject _topMenu`

- `Image _backImage`

- `Image _banner`

- `Text _coinText`

- `UIGachaBoxDrawEffectFloatPage _floatPage`

- `Transform _floatPageContainer`

- `CanvasGroup _alphaHandler`

- `UIGachaBoxDrawEffectFloatPage m_floatPage`

- `Boolean m_isInited`


## Methods

- `Void OnEnable()`

- `Boolean _InitIfNot()`

- `Void OnClick(String)`

- `Void OnClickTence(String)`

- `Void _SendGachaRequest(String, Int32)`

- `Void _SendGachaInfoRequest()`

- `Void _RefreshActWithNewIndex()`

- `Void _RefreshCoinState()`

- `Void ToClueState()`

- `Void <_SendGachaInfoRequest>b__18_0(Act3D0GachaInfoResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0GachaBoxState : PopupFadeState
{
	private Act3D0GachaBoxStateBean _stateBean; // 0x70
	private Act3D0GachaBoxRightPartView _rightPartView; // 0x78
	private Act3D0ClueShowPart _showPart; // 0x80
	private GameObject _topMenu; // 0x88
	private Image _backImage; // 0x90
	private Image _banner; // 0x98
	private Text _coinText; // 0xa0
	private UIGachaBoxDrawEffectFloatPage _floatPage; // 0xa8
	private Transform _floatPageContainer; // 0xb0
	private CanvasGroup _alphaHandler; // 0xb8
	private UIGachaBoxDrawEffectFloatPage m_floatPage; // 0xc0
	private Boolean m_isInited; // 0xc8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_OnClickTence; // 0x20
	private static DelegateBridge __Hotfix0__SendGachaRequest; // 0x28
	private static DelegateBridge __Hotfix0__SendGachaInfoRequest; // 0x30
	private static DelegateBridge __Hotfix0__ReceiveItemsFromBox; // 0x38
	private static DelegateBridge __Hotfix0__RefreshActWithNewIndex; // 0x40
	private static DelegateBridge __Hotfix0__RefreshCoinState; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x50
	private static DelegateBridge __Hotfix0_ToClueState; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x322eb3c VA: 0x7595846b3c
	public Void OnEnable() { }
	// RVA: 0x322ec14 VA: 0x7595846c14
	private Boolean _InitIfNot() { }
	// RVA: 0x322ef38 VA: 0x7595846f38
	public override IStateBean GetCacheBean() { }
	// RVA: 0x322efa0 VA: 0x7595846fa0
	public Void OnClick(String m_boxId) { }
	// RVA: 0x322f2b0 VA: 0x75958472b0
	public Void OnClickTence(String m_boxId) { }
	// RVA: 0x322f024 VA: 0x7595847024
	private Void _SendGachaRequest(String boxId, Int32 count) { }
	// RVA: 0x322ecfc VA: 0x7595846cfc
	private Void _SendGachaInfoRequest() { }
	// RVA: 0x322f3b4 VA: 0x75958473b4
	private static IEnumerator _ReceiveItemsFromBox(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x322f4b8 VA: 0x75958474b8
	private Void _RefreshActWithNewIndex() { }
	// RVA: 0x322f950 VA: 0x7595847950
	private Void _RefreshCoinState() { }
	// RVA: 0x322f9fc VA: 0x75958479fc
	protected override Void OnEnter() { }
	// RVA: 0x322fbc8 VA: 0x7595847bc8
	public Void ToClueState() { }
	// RVA: 0x322fd88 VA: 0x7595847d88
	public Void .ctor() { }
	// RVA: 0x322fdf8 VA: 0x7595847df8
	private Void <_SendGachaInfoRequest>b__18_0(Act3D0GachaInfoResponse response) { }
	// RVA: 0x322fe50 VA: 0x7595847e50
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```