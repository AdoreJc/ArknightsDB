# BossRushStageChooseState

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushStageChooseButtonGroupView _btnGroupView`

- `BossRushStageChooseProgressView _progressView`

- `RectTransform _topContainer`

- `BossRushStageChooseStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _OnJumpToStageDetail(IStateBean)`

- `Void _OnStageGroupClicked(String)`

- `Void _InitIfNot()`

- `Void _RefreshView(Boolean)`

- `Void <_InitIfNot>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageChooseState : PopupFadeState
{
	private BossRushStageChooseButtonGroupView _btnGroupView; // 0x70
	private BossRushStageChooseProgressView _progressView; // 0x78
	private RectTransform _topContainer; // 0x80
	private BossRushStageChooseStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToStageDetail; // 0x20
	private static DelegateBridge __Hotfix0__OnStageGroupClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RefreshView; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2e6fe6c VA: 0x7595487e6c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e6fed4 VA: 0x7595487ed4
	protected override Void OnEnter() { }
	// RVA: 0x2e70268 VA: 0x7595488268
	protected override Void OnResume() { }
	// RVA: 0x2e702fc VA: 0x75954882fc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e70474 VA: 0x7595488474
	private Void _OnJumpToStageDetail(IStateBean stateBean) { }
	// RVA: 0x2e70574 VA: 0x7595488574
	private Void _OnStageGroupClicked(String stageGroupId) { }
	// RVA: 0x2e6ff54 VA: 0x7595487f54
	private Void _InitIfNot() { }
	// RVA: 0x2e700fc VA: 0x75954880fc
	private Void _RefreshView(Boolean showEnterAnim) { }
	// RVA: 0x2e70858 VA: 0x7595488858
	public Void .ctor() { }
	// RVA: 0x2e709b0 VA: 0x75954889b0
	private Void <_InitIfNot>b__11_0() { }
	// RVA: 0x2e70a44 VA: 0x7595488a44
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e70a4c VA: 0x7595488a4c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e70a54 VA: 0x7595488a54
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```