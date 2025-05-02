# RL03DifficultyRulesView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `UIFadeFloatPanel _fadePanel`

- `UIFullScreenImage _background`

- `Text _totemDesc`

- `Text _relicDesc`

- `Text _buffDesc`

- `SimpleLayoutContent _buffList`

- `BuffListAdapter m_buffListAdapter`

- `RoguelikeTopicModeViewProperty m_cachedProp`

- `Coroutine m_hideCo`

- `Action <funcOpenOuterBuff>k__BackingField`

- `Action <funcOpenColection>k__BackingField`


## Properties

- `Action funcOpenOuterBuff`

- `Action funcOpenColection`


## Methods

- `Void set_funcLoadBuffIcon(Func`2)`

- `Action get_funcOpenOuterBuff()`

- `Void set_funcOpenOuterBuff(Action)`

- `Action get_funcOpenColection()`

- `Void set_funcOpenColection(Action)`

- `Void _InitIfNot()`

- `Void Render(RoguelikeTopicModeViewProperty)`

- `Void SetVisible(Boolean)`

- `IEnumerator _DoHide()`

- `Void _CleanRT()`

- `Void OnDestroy()`

- `Void EventOpenOuterBuff()`

- `Void EventOpenCollection()`

- `Void EventCloseView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03DifficultyRulesView : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _fadePanel; // 0x18
	private UIFullScreenImage _background; // 0x20
	private Text _totemDesc; // 0x28
	private Text _relicDesc; // 0x30
	private Text _buffDesc; // 0x38
	private SimpleLayoutContent _buffList; // 0x40
	private BuffListAdapter m_buffListAdapter; // 0x48
	private ListDict`2 m_buffActiveInfo; // 0x50
	private List`1 m_buffList; // 0x58
	private RoguelikeTopicModeViewProperty m_cachedProp; // 0x60
	private Coroutine m_hideCo; // 0x68
	private Func`2 <funcLoadBuffIcon>k__BackingField; // 0x70
	private Action <funcOpenOuterBuff>k__BackingField; // 0x78
	private Action <funcOpenColection>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_get_funcLoadBuffIcon; // 0x0
	private static DelegateBridge __Hotfix0_set_funcLoadBuffIcon; // 0x8
	private static DelegateBridge __Hotfix0_get_funcOpenOuterBuff; // 0x10
	private static DelegateBridge __Hotfix0_set_funcOpenOuterBuff; // 0x18
	private static DelegateBridge __Hotfix0_get_funcOpenColection; // 0x20
	private static DelegateBridge __Hotfix0_set_funcOpenColection; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0_SetVisible; // 0x40
	private static DelegateBridge __Hotfix0__DoHide; // 0x48
	private static DelegateBridge __Hotfix0__CleanRT; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0_EventOpenOuterBuff; // 0x60
	private static DelegateBridge __Hotfix0_EventOpenCollection; // 0x68
	private static DelegateBridge __Hotfix0_EventCloseView; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Func`2 funcLoadBuffIcon { get; set; }
	public Action funcOpenOuterBuff { get; set; }
	public Action funcOpenColection { get; set; }

	// RVA: 0x26a1000 VA: 0x7594cb9000
	public Func`2 get_funcLoadBuffIcon() { }
	// RVA: 0x26a1068 VA: 0x7594cb9068
	public Void set_funcLoadBuffIcon(Func`2 value) { }
	// RVA: 0x26a10ec VA: 0x7594cb90ec
	public Action get_funcOpenOuterBuff() { }
	// RVA: 0x26a1154 VA: 0x7594cb9154
	public Void set_funcOpenOuterBuff(Action value) { }
	// RVA: 0x26a11d8 VA: 0x7594cb91d8
	public Action get_funcOpenColection() { }
	// RVA: 0x26a1240 VA: 0x7594cb9240
	public Void set_funcOpenColection(Action value) { }
	// RVA: 0x26a12c4 VA: 0x7594cb92c4
	private Void _InitIfNot() { }
	// RVA: 0x26a1424 VA: 0x7594cb9424
	public Void Render(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26a179c VA: 0x7594cb979c
	public Void SetVisible(Boolean showRules) { }
	// RVA: 0x26a1990 VA: 0x7594cb9990
	private IEnumerator _DoHide() { }
	// RVA: 0x26a1a64 VA: 0x7594cb9a64
	private Void _CleanRT() { }
	// RVA: 0x26a1bbc VA: 0x7594cb9bbc
	private Void OnDestroy() { }
	// RVA: 0x26a1c24 VA: 0x7594cb9c24
	public Void EventOpenOuterBuff() { }
	// RVA: 0x26a1cc0 VA: 0x7594cb9cc0
	public Void EventOpenCollection() { }
	// RVA: 0x26a1d5c VA: 0x7594cb9d5c
	public Void EventCloseView() { }
	// RVA: 0x26a1e1c VA: 0x7594cb9e1c
	public Void .ctor() { }
}
```