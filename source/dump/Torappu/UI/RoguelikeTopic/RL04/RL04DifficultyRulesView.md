# RL04DifficultyRulesView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `UIFadeFloatPanel _fadePanel`

- `UIFullScreenImage _background`

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
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04DifficultyRulesView : MonoBehaviour, IHotfixable
{
	private UIFadeFloatPanel _fadePanel; // 0x18
	private UIFullScreenImage _background; // 0x20
	private Text _relicDesc; // 0x28
	private Text _buffDesc; // 0x30
	private SimpleLayoutContent _buffList; // 0x38
	private BuffListAdapter m_buffListAdapter; // 0x40
	private RoguelikeTopicModeViewProperty m_cachedProp; // 0x48
	private Coroutine m_hideCo; // 0x50
	private Func`2 <funcLoadBuffIcon>k__BackingField; // 0x58
	private Action <funcOpenOuterBuff>k__BackingField; // 0x60
	private Action <funcOpenColection>k__BackingField; // 0x68
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

	// RVA: 0x26ea484 VA: 0x7594d02484
	public Func`2 get_funcLoadBuffIcon() { }
	// RVA: 0x26ea4ec VA: 0x7594d024ec
	public Void set_funcLoadBuffIcon(Func`2 value) { }
	// RVA: 0x26ea570 VA: 0x7594d02570
	public Action get_funcOpenOuterBuff() { }
	// RVA: 0x26ea5d8 VA: 0x7594d025d8
	public Void set_funcOpenOuterBuff(Action value) { }
	// RVA: 0x26ea65c VA: 0x7594d0265c
	public Action get_funcOpenColection() { }
	// RVA: 0x26ea6c4 VA: 0x7594d026c4
	public Void set_funcOpenColection(Action value) { }
	// RVA: 0x26ea748 VA: 0x7594d02748
	private Void _InitIfNot() { }
	// RVA: 0x26ea8a8 VA: 0x7594d028a8
	public Void Render(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26eab90 VA: 0x7594d02b90
	public Void SetVisible(Boolean showRules) { }
	// RVA: 0x26ead84 VA: 0x7594d02d84
	private IEnumerator _DoHide() { }
	// RVA: 0x26eae58 VA: 0x7594d02e58
	private Void _CleanRT() { }
	// RVA: 0x26eafb0 VA: 0x7594d02fb0
	private Void OnDestroy() { }
	// RVA: 0x26eb018 VA: 0x7594d03018
	public Void EventOpenOuterBuff() { }
	// RVA: 0x26eb0b4 VA: 0x7594d030b4
	public Void EventOpenCollection() { }
	// RVA: 0x26eb150 VA: 0x7594d03150
	public Void EventCloseView() { }
	// RVA: 0x26eb210 VA: 0x7594d03210
	public Void .ctor() { }
}
```