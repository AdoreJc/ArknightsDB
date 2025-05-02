# DeepSeaRPNodeDetailState

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPNodeDetailView _view`

- `RectTransform _backPressRt`

- `Coroutine m_introCoroutine`

- `DeepSeaRPCommonNodeDetailStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _ClearIntroCoroutine()`

- `IEnumerator _IntroCoroutine(EventData, Boolean)`

- `Void _OnChoiceSelected(Int32, EventData)`

- `Void OnBtnLeave()`

- `Void OnBtnAction()`

- `Void OnBtnReadStory()`

- `Void OnBtnOpenChest()`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void <OnBtnLeave>b__12_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPNodeDetailState : PopupFadeState
{
	private DeepSeaRPNodeDetailView _view; // 0x70
	private RectTransform _backPressRt; // 0x78
	private Coroutine m_introCoroutine; // 0x80
	private DeepSeaRPCommonNodeDetailStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnExit; // 0x18
	private static DelegateBridge __Hotfix0__ClearIntroCoroutine; // 0x20
	private static DelegateBridge __Hotfix0__IntroCoroutine; // 0x28
	private static DelegateBridge __Hotfix0__OnChoiceSelected; // 0x30
	private static DelegateBridge __Hotfix0_OnBtnLeave; // 0x38
	private static DelegateBridge __Hotfix0_OnBtnAction; // 0x40
	private static DelegateBridge __Hotfix0_OnBtnReadStory; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnOpenChest; // 0x50
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x29d9f4c VA: 0x7594ff1f4c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29d9fb4 VA: 0x7594ff1fb4
	private Void _InitIfNot() { }
	// RVA: 0x29da0b8 VA: 0x7594ff20b8
	protected override Void OnEnter() { }
	// RVA: 0x29dac40 VA: 0x7594ff2c40
	protected override Void OnExit() { }
	// RVA: 0x29daa10 VA: 0x7594ff2a10
	private Void _ClearIntroCoroutine() { }
	// RVA: 0x29dacb4 VA: 0x7594ff2cb4
	private IEnumerator _IntroCoroutine(EventData eventData, Boolean showAdditionView) { }
	// RVA: 0x29dadbc VA: 0x7594ff2dbc
	private Void _OnChoiceSelected(Int32 choiceIdx, EventData eventData) { }
	// RVA: 0x29db1e4 VA: 0x7594ff31e4
	public Void OnBtnLeave() { }
	// RVA: 0x29db434 VA: 0x7594ff3434
	public Void OnBtnAction() { }
	// RVA: 0x29db568 VA: 0x7594ff3568
	public Void OnBtnReadStory() { }
	// RVA: 0x29db8c0 VA: 0x7594ff38c0
	public Void OnBtnOpenChest() { }
	// RVA: 0x29dbd10 VA: 0x7594ff3d10
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x29dbe10 VA: 0x7594ff3e10
	public Void .ctor() { }
	// RVA: 0x29dbec0 VA: 0x7594ff3ec0
	private Void <OnBtnLeave>b__12_0() { }
	// RVA: 0x29dbed0 VA: 0x7594ff3ed0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x29dbed8 VA: 0x7594ff3ed8
	private Void <>xLuaBaseProxy_OnExit() { }
}
```