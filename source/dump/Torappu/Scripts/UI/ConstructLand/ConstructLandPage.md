# ConstructLandPage

**Namespace:** `Torappu.Scripts.UI.ConstructLand`


## Fields

- `UIFadeFloatPanel _maskView`

- `AnimationWrapper _animEnter`

- `AnimationWrapper _animLoop`

- `Image _maskImg`

- `Text _textTips`

- `GameObject _infoPanel`

- `ConstructLandPageController _sceneBinder`

- `Boolean m_isInited`

- `LoadingShowSwitchTween m_switchTween`

- `Params m_param`

- `Boolean m_alreadyDoLoad`

- `Boolean m_alreadyLoaded`

- `Boolean m_binded`

- `ConstructLandPageProp m_prop`

- `ConstructPageMsg m_pageMsg`


## Properties

- `ConstructLandPageProp prop`

- `ConstructPageMsg pageMsg`


## Methods

- `ConstructLandPageProp get_prop()`

- `ConstructPageMsg get_pageMsg()`

- `Void _InitIfNot()`

- `Boolean RequestExit()`

- `IEnumerator _SetupLoad()`

- `Void _UpdateTextTips()`

- `Void _DoLoadScene()`

- `Void _OnLandLoaded()`

- `IEnumerator _ClosePageWithTrans()`

- `Void _TryUnloadLand()`

- `Void _OnLandUnloaded()`

- `Void Update()`

- `Void _BindIfNot()`

- `Void _TriggerSandboxV2ConstructBGM()`

- `Void _ClearBGM()`

- `Int32 _GetBGMInstId()`

- `IEnumerator _ShowMask()`

- `Void <_DoLoadScene>b__28_0()`

- `Boolean <HideCoroutine>b__41_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.ConstructLand
public class ConstructLandPage : UIPage, ConstructBattleSceneUser
{
	private UIFadeFloatPanel _maskView; // 0xd0
	private AnimationWrapper _animEnter; // 0xd8
	private AnimationWrapper _animLoop; // 0xe0
	private Image _maskImg; // 0xe8
	private Text _textTips; // 0xf0
	private GameObject _infoPanel; // 0xf8
	private ConstructLandPageController _sceneBinder; // 0x100
	private Boolean m_isInited; // 0x108
	private LoadingShowSwitchTween m_switchTween; // 0x110
	private const Single MASK_MIN_TIME; // 0x0
	private Params m_param; // 0x118
	private Boolean m_alreadyDoLoad; // 0x150
	private Boolean m_alreadyLoaded; // 0x151
	private Boolean m_binded; // 0x152
	private ConstructLandPageProp m_prop; // 0x158
	private ConstructPageMsg m_pageMsg; // 0x160
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_get_pageMsg; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge __Hotfix0_RequestExit; // 0x28
	private static DelegateBridge __Hotfix0__SetupLoad; // 0x30
	private static DelegateBridge __Hotfix0__UpdateTextTips; // 0x38
	private static DelegateBridge __Hotfix0__DoLoadScene; // 0x40
	private static DelegateBridge __Hotfix0__OnLandLoaded; // 0x48
	private static DelegateBridge __Hotfix0__ClosePageWithTrans; // 0x50
	private static DelegateBridge __Hotfix0__TryUnloadLand; // 0x58
	private static DelegateBridge __Hotfix0__OnLandUnloaded; // 0x60
	private static DelegateBridge __Hotfix0_OnStart; // 0x68
	private static DelegateBridge __Hotfix0_OnStop; // 0x70
	private static DelegateBridge __Hotfix0_Update; // 0x78
	private static DelegateBridge __Hotfix0__BindIfNot; // 0x80
	private static DelegateBridge __Hotfix0__TriggerSandboxV2ConstructBGM; // 0x88
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x90
	private static DelegateBridge __Hotfix0__GetBGMInstId; // 0x98
	private static DelegateBridge __Hotfix0__ShowMask; // 0xa0
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public ConstructLandPageProp prop { get; }
	public ConstructPageMsg pageMsg { get; }

	// RVA: 0x37721a0 VA: 0x7595d8a1a0
	public ConstructLandPageProp get_prop() { }
	// RVA: 0x3772208 VA: 0x7595d8a208
	public ConstructPageMsg get_pageMsg() { }
	// RVA: 0x3772270 VA: 0x7595d8a270
	private Void _InitIfNot() { }
	// RVA: 0x377242c VA: 0x7595d8a42c
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x3772aa4 VA: 0x7595d8aaa4
	protected override Void OnDestroy() { }
	// RVA: 0x3772bfc VA: 0x7595d8abfc
	public Boolean RequestExit() { }
	// RVA: 0x37729f8 VA: 0x7595d8a9f8
	private IEnumerator _SetupLoad() { }
	// RVA: 0x3772d50 VA: 0x7595d8ad50
	private Void _UpdateTextTips() { }
	// RVA: 0x3772efc VA: 0x7595d8aefc
	private Void _DoLoadScene() { }
	// RVA: 0x37730e8 VA: 0x7595d8b0e8
	private Void _OnLandLoaded() { }
	// RVA: 0x3772c7c VA: 0x7595d8ac7c
	private IEnumerator _ClosePageWithTrans() { }
	// RVA: 0x3772b18 VA: 0x7595d8ab18
	private Void _TryUnloadLand() { }
	// RVA: 0x37731d4 VA: 0x7595d8b1d4
	private Void _OnLandUnloaded() { }
	// RVA: 0x3773294 VA: 0x7595d8b294
	protected override Void OnStart() { }
	// RVA: 0x3773460 VA: 0x7595d8b460
	protected override Void OnStop() { }
	// RVA: 0x37735dc VA: 0x7595d8b5dc
	private Void Update() { }
	// RVA: 0x3773644 VA: 0x7595d8b644
	private Void _BindIfNot() { }
	// RVA: 0x3773710 VA: 0x7595d8b710
	private Void _TriggerSandboxV2ConstructBGM() { }
	// RVA: 0x3773534 VA: 0x7595d8b534
	private Void _ClearBGM() { }
	// RVA: 0x3773838 VA: 0x7595d8b838
	private Int32 _GetBGMInstId() { }
	// RVA: 0x37738a4 VA: 0x7595d8b8a4
	private IEnumerator _ShowMask() { }
	// RVA: 0x3773978 VA: 0x7595d8b978
	protected override IEnumerator HideCoroutine(Boolean isIntoStack) { }
	// RVA: 0x3773a68 VA: 0x7595d8ba68
	public Void .ctor() { }
	// RVA: 0x3773ad8 VA: 0x7595d8bad8
	private Void <_DoLoadScene>b__28_0() { }
	// RVA: 0x3773ae0 VA: 0x7595d8bae0
	private Boolean <HideCoroutine>b__41_0() { }
	// RVA: 0x3773af0 VA: 0x7595d8baf0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3773af8 VA: 0x7595d8baf8
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x3773b00 VA: 0x7595d8bb00
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3773b08 VA: 0x7595d8bb08
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x3773b10 VA: 0x7595d8bb10
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(Boolean P0) { }
}
```