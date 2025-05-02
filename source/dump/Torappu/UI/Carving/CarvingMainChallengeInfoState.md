# CarvingMainChallengeInfoState

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIFullScreenImage _background`

- `CarvingMainChallengeInfoView _infoView`

- `RectTransform _backBtn`

- `GameObject _autoPopBkgObj`

- `UIAnimationLocation _showAnimLocation`

- `CarvingMainChallengeInfoStateBean m_stateBean`

- `Boolean m_isInited`

- `Tween m_showTween`


## Methods

- `Void _InitIfNot()`

- `Void _PlayShowAnim()`

- `Void OnClickBackBtn()`

- `Void _OnClickState(CarvingShopToBuyResponse)`

- `Void _OnBackBtnClicked()`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainChallengeInfoState : PopupFadeState
{
	private UIFullScreenImage _background; // 0x70
	private CarvingMainChallengeInfoView _infoView; // 0x78
	private RectTransform _backBtn; // 0x80
	private GameObject _autoPopBkgObj; // 0x88
	private UIAnimationLocation _showAnimLocation; // 0x90
	private CarvingMainChallengeInfoStateBean m_stateBean; // 0xa0
	private Boolean m_isInited; // 0xa8
	private Tween m_showTween; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__PlayShowAnim; // 0x20
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x28
	private static DelegateBridge __Hotfix0__OnClickState; // 0x30
	private static DelegateBridge __Hotfix0__OnBackBtnClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2dab900 VA: 0x75953c3900
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2dab968 VA: 0x75953c3968
	protected override Void OnEnter() { }
	// RVA: 0x2dac140 VA: 0x75953c4140
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2dabb54 VA: 0x75953c3b54
	private Void _InitIfNot() { }
	// RVA: 0x2dabc88 VA: 0x75953c3c88
	private Void _PlayShowAnim() { }
	// RVA: 0x2dac2d4 VA: 0x75953c42d4
	public Void OnClickBackBtn() { }
	// RVA: 0x2dac7a0 VA: 0x75953c47a0
	private Void _OnClickState(CarvingShopToBuyResponse response) { }
	// RVA: 0x2dac5dc VA: 0x75953c45dc
	private Void _OnBackBtnClicked() { }
	// RVA: 0x2dac92c VA: 0x75953c492c
	public Void .ctor() { }
	// RVA: 0x2daca84 VA: 0x75953c4a84
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x2dacaac VA: 0x75953c4aac
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2dacab4 VA: 0x75953c4ab4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```