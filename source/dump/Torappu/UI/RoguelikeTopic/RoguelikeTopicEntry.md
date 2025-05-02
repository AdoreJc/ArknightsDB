# RoguelikeTopicEntry

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicModeViewModelExtension _modelExtension`

- `DisplayParentConfig _displayParentConfig`

- `Boolean m_isInited`

- `UITwoStepAnimation m_animPlayer`

- `Bridge m_bridge`

- `Coroutine m_showEffectCoroutine`

- `String <topicId>k__BackingField`


## Properties

- `RoguelikeTopicModeViewModelExtension extensionModel`

- `String topicId`


## Methods

- `RoguelikeTopicModeViewModelExtension get_extensionModel()`

- `String get_topicId()`

- `Void set_topicId(String)`

- `Void EventOnAnnounceClicked()`

- `Void EventOnOpenBattlePath()`

- `Void Init(Bridge, RoguelikeTopicController)`

- `DisplayParentConfig GetDisplayParentConfig(Boolean)`

- `Coroutine StartShowEffect(Boolean)`

- `Void SetEffectsEnable(Boolean)`

- `Void _TriggerTopicAvg(String, Action)`

- `IEnumerator _ShowEffectCoroutine(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicEntry : MonoBehaviour, IHotfixable
{
	private const String ROGUELIKE_TOPIC_ENTRY_AVG_TRIGGER; // 0x0
	private RoguelikeTopicModeViewModelExtension _modelExtension; // 0x18
	private RoguelikeTopicModeTab[] _tabs; // 0x20
	private RoguelikeTopicViewHolder[] _stableViewHolders; // 0x28
	private RoguelikeTopicSubView[] _stableViews; // 0x30
	private UIAnimationLocation[] _enterAnims; // 0x38
	private UIAnimationLocation[] _loopAnims; // 0x40
	private UICommonPageEffectHolder[] _effectHolders; // 0x48
	private Canvas[] _canvases; // 0x50
	private DisplayParentConfig _displayParentConfig; // 0x58
	private Boolean m_isInited; // 0x60
	private UITwoStepAnimation m_animPlayer; // 0x68
	private Bridge m_bridge; // 0x70
	private Coroutine m_showEffectCoroutine; // 0x78
	private String <topicId>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_extensionModel; // 0x0
	private static DelegateBridge __Hotfix0_get_topicId; // 0x8
	private static DelegateBridge __Hotfix0_set_topicId; // 0x10
	private static DelegateBridge __Hotfix0_EventOnAnnounceClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnOpenBattlePath; // 0x20
	private static DelegateBridge __Hotfix0_Init; // 0x28
	private static DelegateBridge __Hotfix0_GetDisplayParentConfig; // 0x30
	private static DelegateBridge __Hotfix0_StartShowEffect; // 0x38
	private static DelegateBridge __Hotfix0_SetEffectsEnable; // 0x40
	private static DelegateBridge __Hotfix0__TriggerTopicAvg; // 0x48
	private static DelegateBridge __Hotfix0__ShowEffectCoroutine; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public RoguelikeTopicModeViewModelExtension extensionModel { get; }
	protected String topicId { get; set; }

	// RVA: 0x266c664 VA: 0x7594c84664
	public RoguelikeTopicModeViewModelExtension get_extensionModel() { }
	// RVA: 0x266c6cc VA: 0x7594c846cc
	protected String get_topicId() { }
	// RVA: 0x266c734 VA: 0x7594c84734
	private Void set_topicId(String value) { }
	// RVA: 0x266c7b8 VA: 0x7594c847b8
	public Void EventOnAnnounceClicked() { }
	// RVA: 0x266c834 VA: 0x7594c84834
	public Void EventOnOpenBattlePath() { }
	// RVA: 0x266c8b0 VA: 0x7594c848b0
	public Void Init(Bridge bridge, RoguelikeTopicController controller) { }
	// RVA: 0x266ccf0 VA: 0x7594c84cf0
	public DisplayParentConfig GetDisplayParentConfig(Boolean useFastMode) { }
	// RVA: 0x266cd9c VA: 0x7594c84d9c
	public Coroutine StartShowEffect(Boolean fastMode) { }
	// RVA: 0x266cf44 VA: 0x7594c84f44
	public Void SetEffectsEnable(Boolean isEnable) { }
	// RVA: 0x266d194 VA: 0x7594c85194
	private Void _TriggerTopicAvg(String topicId, Action nextStep) { }
	// RVA: 0x266ce7c VA: 0x7594c84e7c
	private IEnumerator _ShowEffectCoroutine(Boolean useFastMode) { }
	// RVA: 0x266d370 VA: 0x7594c85370
	public Void .ctor() { }
}
```