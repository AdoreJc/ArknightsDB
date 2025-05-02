# FireworkCraftAnimalSelectState

**Namespace:** `Torappu.UI.Firework.FireworkCraft`


## Fields

- `RectTransform _topMenuHolder`

- `FireworkCraftAnimalSelectView _view`

- `Boolean m_inited`

- `StateBean m_stateBean`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnBackBtnClicked()`

- `Void _OnAnimalClicked(String)`

- `Void _OnEquipClicked()`

- `Void _OnAnimalChangeProceed(FireworkChangeAnimalResponse)`

- `Boolean _IsUIStable()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkCraft
public class FireworkCraftAnimalSelectState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_ANIMAL_CLICKED; // 0x0
	public const Int32 ON_EQUIP_BTN_CLICKED; // 0x0
	private RectTransform _topMenuHolder; // 0x70
	private FireworkCraftAnimalSelectView _view; // 0x78
	private Boolean m_inited; // 0x80
	private StateBean m_stateBean; // 0x88
	private Coroutine m_tutorialCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPause; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__EventOnBackBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnAnimalClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnEquipClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnAnimalChangeProceed; // 0x48
	private static DelegateBridge __Hotfix0__IsUIStable; // 0x50
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x58
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2900e7c VA: 0x7594f18e7c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2900ee4 VA: 0x7594f18ee4
	protected override Void OnEnter() { }
	// RVA: 0x29014c4 VA: 0x7594f194c4
	protected override Void OnPause() { }
	// RVA: 0x29015e0 VA: 0x7594f195e0
	protected override Void OnResume() { }
	// RVA: 0x2900fbc VA: 0x7594f18fbc
	private Void _InitIfNot() { }
	// RVA: 0x2901890 VA: 0x7594f19890
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2901d60 VA: 0x7594f19d60
	private Void _EventOnBackBtnClicked() { }
	// RVA: 0x290197c VA: 0x7594f1997c
	private Void _OnAnimalClicked(String animalId) { }
	// RVA: 0x2901a78 VA: 0x7594f19a78
	private Void _OnEquipClicked() { }
	// RVA: 0x29020b0 VA: 0x7594f1a0b0
	private Void _OnAnimalChangeProceed(FireworkChangeAnimalResponse response) { }
	// RVA: 0x2901dec VA: 0x7594f19dec
	private Boolean _IsUIStable() { }
	// RVA: 0x2901670 VA: 0x7594f19670
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2901538 VA: 0x7594f19538
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2902340 VA: 0x7594f1a340
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2902414 VA: 0x7594f1a414
	public Void .ctor() { }
	// RVA: 0x290256c VA: 0x7594f1a56c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2902574 VA: 0x7594f1a574
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x290257c VA: 0x7594f1a57c
	private Void <>xLuaBaseProxy_OnResume() { }
}
```