# RoguelikeTransitionView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _mainTransHolder`

- `Transform _subTransHolder`

- `Boolean m_isInited`

- `String m_topicId`

- `RoguelikeMainTransController m_mainTransController`

- `RoguelikeSubTransitionPluginContext m_subTransPlugin`

- `RoguelikeDungeonState <state>k__BackingField`

- `TransController m_transController`


## Properties

- `RoguelikeDungeonState state`


## Methods

- `RoguelikeDungeonState get_state()`

- `Void set_state(RoguelikeDungeonState)`

- `Void _InitIfNot(String)`

- `Void _LoadMainTransControllerIfNot(String)`

- `Void _DestroyMainTransView()`

- `Void _DestroySubTransView()`

- `IEnumerator StartShowTransition(RoguelikeDungeonZoneViewProperty, TransOptions)`

- `Void InterruptShowTransition()`

- `IEnumerator _ShowMainTransition()`

- `IEnumerator _ShowSubTransition(SubTransType, TransOptions)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeTransitionView : MonoBehaviour, IHotfixable
{
	private Transform _mainTransHolder; // 0x18
	private Transform _subTransHolder; // 0x20
	private Boolean m_isInited; // 0x28
	private String m_topicId; // 0x30
	private RoguelikeMainTransController m_mainTransController; // 0x38
	private RoguelikeSubTransitionPluginContext m_subTransPlugin; // 0x40
	private RoguelikeDungeonState <state>k__BackingField; // 0x48
	private TransController m_transController; // 0x50
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__LoadMainTransControllerIfNot; // 0x18
	private static DelegateBridge __Hotfix0__DestroyMainTransView; // 0x20
	private static DelegateBridge __Hotfix0__DestroySubTransView; // 0x28
	private static DelegateBridge __Hotfix0_StartShowTransition; // 0x30
	private static DelegateBridge __Hotfix0_InterruptShowTransition; // 0x38
	private static DelegateBridge __Hotfix0__ShowMainTransition; // 0x40
	private static DelegateBridge __Hotfix0__ShowSubTransition; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private RoguelikeDungeonState state { get; set; }

	// RVA: 0x2a16830 VA: 0x759502e830
	private RoguelikeDungeonState get_state() { }
	// RVA: 0x2a16898 VA: 0x759502e898
	public Void set_state(RoguelikeDungeonState value) { }
	// RVA: 0x2a1691c VA: 0x759502e91c
	private Void _InitIfNot(String topicId) { }
	// RVA: 0x2a169fc VA: 0x759502e9fc
	private Void _LoadMainTransControllerIfNot(String topicId) { }
	// RVA: 0x2a16fc8 VA: 0x759502efc8
	private Void _DestroyMainTransView() { }
	// RVA: 0x2a1709c VA: 0x759502f09c
	private Void _DestroySubTransView() { }
	// RVA: 0x2a17170 VA: 0x759502f170
	public IEnumerator StartShowTransition(RoguelikeDungeonZoneViewProperty property, TransOptions options) { }
	// RVA: 0x2a172a4 VA: 0x759502f2a4
	public Void InterruptShowTransition() { }
	// RVA: 0x2a17580 VA: 0x759502f580
	private IEnumerator _ShowMainTransition() { }
	// RVA: 0x2a1762c VA: 0x759502f62c
	private IEnumerator _ShowSubTransition(SubTransType subTransType, TransOptions transOptions) { }
	// RVA: 0x2a1772c VA: 0x759502f72c
	public Void .ctor() { }
}
```