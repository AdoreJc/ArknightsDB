# TuningProductConfirmState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `UIAnimationLocation _enterAnimLocation`

- `TuningProductConfirmView _confirmView`

- `RectTransform _backBtn`

- `TuningProductConfirmStateBean m_stateBean`

- `Sequence m_enterSequence`

- `Boolean m_isInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _PlayMusic()`

- `Void _InitIfNot()`

- `Void _OnPressBackBtn()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductConfirmState : PopupFadeState, IValueMsgReceiver
{
	private const Single ENTRY_AUDIO_DELAY; // 0x0
	private UIAnimationLocation _enterAnimLocation; // 0x70
	private TuningProductConfirmView _confirmView; // 0x80
	private RectTransform _backBtn; // 0x88
	private TuningProductConfirmStateBean m_stateBean; // 0x90
	private Sequence m_enterSequence; // 0x98
	private Boolean m_isInited; // 0xa0
	public const Int32 CONFIRM_PRODUCT; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__PlayMusic; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnPressBackBtn; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2345074 VA: 0x759495d074
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23450dc VA: 0x759495d0dc
	protected override Void OnEnter() { }
	// RVA: 0x2345638 VA: 0x759495d638
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2345804 VA: 0x759495d804
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2345440 VA: 0x759495d440
	private Void _PlayMusic() { }
	// RVA: 0x2345218 VA: 0x759495d218
	private Void _InitIfNot() { }
	// RVA: 0x23456dc VA: 0x759495d6dc
	private Void _OnPressBackBtn() { }
	// RVA: 0x2345ce0 VA: 0x759495dce0
	public Void .ctor() { }
	// RVA: 0x2345e38 VA: 0x759495de38
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2345e40 VA: 0x759495de40
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```