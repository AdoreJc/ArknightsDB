# Act36sideFoodHandbookPage

**Namespace:** `Torappu.Activity.Act36side`


## Fields

- `Act36sideFoodHandbookView _view`

- `UIRenderTextureImage _blurBg`

- `RectTransform _closeArea`

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _rightPanelEnterAnim`

- `Act36sideFoodHandbookProperty m_property`

- `Tween m_enterAnimTween`

- `Tween m_rightPanelEnterTween`


## Methods

- `Void _PlayAnimFromBegin(UIAnimationLocation, ref)`

- `Void _PlayEnterAudio()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _ClosePage()`

- `Void _SwitchTab(Act36sideFoodHandbookTabType)`

- `Void _SelectToken(String)`

- `Void _ClaimReward()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act36side
public class Act36sideFoodHandbookPage : UIPage, IValueMsgReceiver
{
	public const Int32 CLOSE_PAGE; // 0x0
	public const Int32 SWITCH_TAB; // 0x0
	public const Int32 SELECT_TOKEN; // 0x0
	public const Int32 CLAIM_REWARD; // 0x0
	private Act36sideFoodHandbookView _view; // 0xd0
	private UIRenderTextureImage _blurBg; // 0xd8
	private RectTransform _closeArea; // 0xe0
	private UIAnimationLocation _enterAnim; // 0xe8
	private UIAnimationLocation _rightPanelEnterAnim; // 0xf8
	private Act36sideFoodHandbookProperty m_property; // 0x108
	private Tween m_enterAnimTween; // 0x110
	private Tween m_rightPanelEnterTween; // 0x118
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__PlayAnimFromBegin; // 0x10
	private static DelegateBridge __Hotfix0__PlayEnterAudio; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__ClosePage; // 0x28
	private static DelegateBridge __Hotfix0__SwitchTab; // 0x30
	private static DelegateBridge __Hotfix0__SelectToken; // 0x38
	private static DelegateBridge __Hotfix0__ClaimReward; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3245218 VA: 0x759585d218
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x3245cc8 VA: 0x759585dcc8
	public override IEnumerator ShowCoroutine(Boolean isFromStack) { }
	// RVA: 0x3245db8 VA: 0x759585ddb8
	private Void _PlayAnimFromBegin(UIAnimationLocation location, ref Tween tween) { }
	// RVA: 0x3245eec VA: 0x759585deec
	private Void _PlayEnterAudio() { }
	// RVA: 0x324600c VA: 0x759585e00c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x324611c VA: 0x759585e11c
	private Void _ClosePage() { }
	// RVA: 0x324619c VA: 0x759585e19c
	private Void _SwitchTab(Act36sideFoodHandbookTabType selectType) { }
	// RVA: 0x3246280 VA: 0x759585e280
	private Void _SelectToken(String selectTokenId) { }
	// RVA: 0x3246350 VA: 0x759585e350
	private Void _ClaimReward() { }
	// RVA: 0x3246850 VA: 0x759585e850
	public Void .ctor() { }
	// RVA: 0x3246968 VA: 0x759585e968
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3246970 VA: 0x759585e970
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(Boolean P0) { }
}
```