# Act24sideMissionState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionView _view`

- `UIAnimationLocation _anim`

- `RectTransform _backRect`

- `Act24sideMissionStateBean m_stateBean`

- `TemplateActivityController m_cacheController`

- `Tween m_entryTween`

- `Boolean m_isInited`


## Methods

- `Void _RefreshData()`

- `Void _RefreshStageMeldingData()`

- `Void _RefreshEntryMissionData()`

- `Void _InitIfNot()`

- `Void _OnEnterDetailState(IStateBean)`

- `Void BindController(TemplateActivityController)`

- `Void _OnClickDetailBtn(String)`

- `Void _OnClickCompleleBtn(String)`

- `Void _OnClickOneClickBtn()`

- `Void OnClickBackBtn()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_OnClickCompleleBtn>b__19_0(ActivityConfirmMissionResponse)`

- `Void <_OnClickOneClickBtn>b__20_0(ActivityMissionCheckResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionState : PopupFadeState, IBaseActStateHolder, IHotfixable
{
	private Act24sideMissionView _view; // 0x70
	private UIAnimationLocation _anim; // 0x78
	private RectTransform _backRect; // 0x88
	private Act24sideMissionStateBean m_stateBean; // 0x90
	private TemplateActivityController m_cacheController; // 0x98
	private Tween m_entryTween; // 0xa0
	private Boolean m_isInited; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__RefreshData; // 0x20
	private static DelegateBridge __Hotfix0__RefreshStageMeldingData; // 0x28
	private static DelegateBridge __Hotfix0__RefreshEntryMissionData; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__OnEnterDetailState; // 0x40
	private static DelegateBridge __Hotfix0_BindController; // 0x48
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x50
	private static DelegateBridge __Hotfix0__OnClickDetailBtn; // 0x58
	private static DelegateBridge __Hotfix0__OnClickCompleleBtn; // 0x60
	private static DelegateBridge __Hotfix0__OnClickOneClickBtn; // 0x68
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x70
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x32bd314 VA: 0x75958d5314
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32bd37c VA: 0x75958d537c
	protected override Void OnEnter() { }
	// RVA: 0x32bd7d0 VA: 0x75958d57d0
	protected override Void OnResume() { }
	// RVA: 0x32bd8e0 VA: 0x75958d58e0
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x32bd844 VA: 0x75958d5844
	private Void _RefreshData() { }
	// RVA: 0x32bdb08 VA: 0x75958d5b08
	private Void _RefreshStageMeldingData() { }
	// RVA: 0x32bdc44 VA: 0x75958d5c44
	private Void _RefreshEntryMissionData() { }
	// RVA: 0x32bd4b0 VA: 0x75958d54b0
	private Void _InitIfNot() { }
	// RVA: 0x32bdd80 VA: 0x75958d5d80
	private Void _OnEnterDetailState(IStateBean stateBean) { }
	// RVA: 0x32bde68 VA: 0x75958d5e68
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x32bdeec VA: 0x75958d5eec
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32be064 VA: 0x75958d6064
	private Void _OnClickDetailBtn(String missionId) { }
	// RVA: 0x32be218 VA: 0x75958d6218
	private Void _OnClickCompleleBtn(String missionId) { }
	// RVA: 0x32be48c VA: 0x75958d648c
	private Void _OnClickOneClickBtn() { }
	// RVA: 0x32be990 VA: 0x75958d6990
	public Void OnClickBackBtn() { }
	// RVA: 0x32beaa4 VA: 0x75958d6aa4
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x32beb9c VA: 0x75958d6b9c
	public Void .ctor() { }
	// RVA: 0x32becf4 VA: 0x75958d6cf4
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x32bed1c VA: 0x75958d6d1c
	private Void <_OnClickCompleleBtn>b__19_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x32bed78 VA: 0x75958d6d78
	private Void <_OnClickOneClickBtn>b__20_0(ActivityMissionCheckResponse response) { }
	// RVA: 0x32bedd4 VA: 0x75958d6dd4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32beddc VA: 0x75958d6ddc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x32bede4 VA: 0x75958d6de4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x32bee0c VA: 0x75958d6e0c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```