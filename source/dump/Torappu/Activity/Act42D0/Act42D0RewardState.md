# Act42D0RewardState

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Act42D0RewardView _rewardView`

- `RectTransform _backRt`

- `Boolean m_isInited`

- `String m_actId`

- `Act42D0RewardProperty m_property`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSelectArea(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardState : PopupFloatState, IValueMsgReceiver
{
	private Act42D0RewardView _rewardView; // 0x70
	private RectTransform _backRt; // 0x78
	private Boolean m_isInited; // 0x80
	private String m_actId; // 0x88
	private Act42D0RewardProperty m_property; // 0x90
	public const Int32 MSG_SELECT_AREA; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0__OnSelectArea; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x321fa24 VA: 0x7595837a24
	public override IStateBean GetCacheBean() { }
	// RVA: 0x321fa88 VA: 0x7595837a88
	protected override Void OnEnter() { }
	// RVA: 0x32209b8 VA: 0x75958389b8
	protected override Void OnResume() { }
	// RVA: 0x321fc4c VA: 0x7595837c4c
	private Void _InitIfNot() { }
	// RVA: 0x3220fa4 VA: 0x7595838fa4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x322104c VA: 0x759583904c
	private Void _OnSelectArea(String areaId) { }
	// RVA: 0x3221164 VA: 0x7595839164
	public Void .ctor() { }
	// RVA: 0x322127c VA: 0x759583927c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3221284 VA: 0x7595839284
	private Void <>xLuaBaseProxy_OnResume() { }
}
```