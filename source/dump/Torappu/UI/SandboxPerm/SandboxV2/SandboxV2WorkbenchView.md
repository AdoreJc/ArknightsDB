# SandboxV2WorkbenchView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single SWITCH_MID_INTERVAL`

- `SimpleLayoutContent _materialContent`

- `CanvasGroup _itemsGroup`

- `SandboxV2WorkbenchLoopAdapter _itemLoopAdapter`

- `LoopVerticalScrollRect _itemScrollRect`

- `GameObject _itemsPanel`

- `GameObject _emptyPanel`

- `GameObject _filterPanel`

- `GameObject _filterActivePanel`

- `GameObject _filterInactivePanel`

- `GameObject _goldPanel`

- `Text _goldText`

- `Single _typeSwitchHalfDuration`

- `Boolean m_hasInited`

- `Adapter m_materialAdapter`

- `Tween m_typeSwitchTween`

- `Boolean m_blockingItemsUpdate`

- `String m_cachedTopicId`

- `SandboxV2AdminMainWorkbenchType m_cachedType`

- `Boolean m_cachedFilter`

- `Action <setFilterCanMakeEvent>k__BackingField`

- `SandboxV2AdminMainState <tutorialOnly_mainState>k__BackingField`

- `Coroutine m_tutorialRaisingCoroutine`


## Properties

- `Action setFilterCanMakeEvent`

- `SandboxV2AdminMainState tutorialOnly_mainState`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Action get_setFilterCanMakeEvent()`

- `Void set_setFilterCanMakeEvent(Action)`

- `Void OnSetFilterCanMakeEvent()`

- `Void _InitIfNot()`

- `Void _SwitchContent()`

- `Sequence _SequenceOfSwitchContent()`

- `SandboxV2AdminMainState get_tutorialOnly_mainState()`

- `Void set_tutorialOnly_mainState(SandboxV2AdminMainState)`

- `Void _TutorialOnly_CheckSignalToRaise()`

- `IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action)`

- `Void _StopCoroutineIfNeed()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2WorkbenchView : DataBinder`1
{
	private Single SWITCH_MID_INTERVAL; // 0x20
	private SimpleLayoutContent _materialContent; // 0x28
	private CanvasGroup _itemsGroup; // 0x30
	private SandboxV2WorkbenchLoopAdapter _itemLoopAdapter; // 0x38
	private LoopVerticalScrollRect _itemScrollRect; // 0x40
	private GameObject _itemsPanel; // 0x48
	private GameObject _emptyPanel; // 0x50
	private GameObject _filterPanel; // 0x58
	private GameObject _filterActivePanel; // 0x60
	private GameObject _filterInactivePanel; // 0x68
	private GameObject _goldPanel; // 0x70
	private Text _goldText; // 0x78
	private Single _typeSwitchHalfDuration; // 0x80
	private Boolean m_hasInited; // 0x84
	private Adapter m_materialAdapter; // 0x88
	private Tween m_typeSwitchTween; // 0x90
	private Boolean m_blockingItemsUpdate; // 0x98
	private String m_cachedTopicId; // 0xa0
	private List`1 m_cachedMaterials; // 0xa8
	private SandboxV2AdminMainWorkbenchType m_cachedType; // 0xb0
	private List`1 m_cachedItems; // 0xb8
	private Boolean m_cachedFilter; // 0xc0
	private Action`1 <itemSelectEvent>k__BackingField; // 0xc8
	private Action <setFilterCanMakeEvent>k__BackingField; // 0xd0
	private SandboxV2AdminMainState <tutorialOnly_mainState>k__BackingField; // 0xd8
	private Coroutine m_tutorialRaisingCoroutine; // 0xe0
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_setFilterCanMakeEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_setFilterCanMakeEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnSetFilterCanMakeEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__SwitchContent; // 0x38
	private static DelegateBridge __Hotfix0__SequenceOfSwitchContent; // 0x40
	private static DelegateBridge __Hotfix0_get_tutorialOnly_mainState; // 0x48
	private static DelegateBridge __Hotfix0_set_tutorialOnly_mainState; // 0x50
	private static DelegateBridge __Hotfix0__TutorialOnly_CheckSignalToRaise; // 0x58
	private static DelegateBridge __Hotfix0__TutorialOnly_RaiseSignalWhenFinishTransiting; // 0x60
	private static DelegateBridge __Hotfix0__StopCoroutineIfNeed; // 0x68
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Action`1 itemSelectEvent { get; set; }
	private Action setFilterCanMakeEvent { get; set; }
	private SandboxV2AdminMainState tutorialOnly_mainState { get; set; }

	// RVA: 0x24f64ec VA: 0x7594b0e4ec
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x24ed3d0 VA: 0x7594b053d0
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x24f6554 VA: 0x7594b0e554
	private Action get_setFilterCanMakeEvent() { }
	// RVA: 0x24ed454 VA: 0x7594b05454
	public Void set_setFilterCanMakeEvent(Action value) { }
	// RVA: 0x24f65bc VA: 0x7594b0e5bc
	public Void OnSetFilterCanMakeEvent() { }
	// RVA: 0x24f6658 VA: 0x7594b0e658
	public override Void OnValueChanged(SandboxV2AdminMainWorkbenchPanelModelProperty property) { }
	// RVA: 0x24f68f8 VA: 0x7594b0e8f8
	private Void _InitIfNot() { }
	// RVA: 0x24f69e8 VA: 0x7594b0e9e8
	private Void _SwitchContent() { }
	// RVA: 0x24f6b58 VA: 0x7594b0eb58
	private Sequence _SequenceOfSwitchContent() { }
	// RVA: 0x24f6f1c VA: 0x7594b0ef1c
	private SandboxV2AdminMainState get_tutorialOnly_mainState() { }
	// RVA: 0x24ed774 VA: 0x7594b05774
	public Void set_tutorialOnly_mainState(SandboxV2AdminMainState value) { }
	// RVA: 0x24f6cd8 VA: 0x7594b0ecd8
	private Void _TutorialOnly_CheckSignalToRaise() { }
	// RVA: 0x24f70a4 VA: 0x7594b0f0a4
	private IEnumerator _TutorialOnly_RaiseSignalWhenFinishTransiting(Action signalAction) { }
	// RVA: 0x24f6f84 VA: 0x7594b0ef84
	private Void _StopCoroutineIfNeed() { }
	// RVA: 0x24f719c VA: 0x7594b0f19c
	private Void OnDestroy() { }
	// RVA: 0x24f7204 VA: 0x7594b0f204
	public Void .ctor() { }
}
```