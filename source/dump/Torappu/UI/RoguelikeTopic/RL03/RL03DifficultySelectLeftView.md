# RL03DifficultySelectLeftView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `GameObject _buffActiveBg`

- `GameObject _buffDisactiveBg`

- `GameObject _predictPanel`

- `GameObject _buffPanel`

- `Text _predictTips`

- `Text _bpNum`

- `Text _bossNum`

- `GameObject _addRoot`

- `Text _totemProb`

- `Text _relicDevLevel`

- `Sprite _lockedBuffSprite`

- `Text _buffActiveTips`

- `UIAnimationLocation _buffSwitchAnim`

- `RoguelikeTopicModeViewProperty m_cachedProp`

- `Int32 m_currSel`

- `Single m_animPos`

- `Tween m_animTween`


## Methods

- `Void set_buffIconLoader(Func`2)`

- `Void Render(RoguelikeTopicModeViewProperty)`

- `RoguelikeTopicDifficultyViewModel _FindBuffDifficultyModel(RoguelikeTopicModeViewModel)`

- `RoguelikeTopicDifficultyViewModel _FindDificultyModel(RoguelikeTopicModeViewModel, RoguelikeTopicMode, Int32)`

- `Void UpdateSelect(RL03DifficultyViewModel, Int32, Boolean)`

- `Void _TweenBuffIconTo(Int32, Boolean)`

- `Void EventShowAddDetail()`

- `Void EventShowRules()`

- `Single <_TweenBuffIconTo>b__26_0()`

- `Void <_TweenBuffIconTo>b__26_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class RL03DifficultySelectLeftView : MonoBehaviour, IHotfixable
{
	private GameObject _buffActiveBg; // 0x18
	private GameObject _buffDisactiveBg; // 0x20
	private GameObject _predictPanel; // 0x28
	private GameObject _buffPanel; // 0x30
	private Text _predictTips; // 0x38
	private Text _bpNum; // 0x40
	private Text _bossNum; // 0x48
	private GameObject _addRoot; // 0x50
	private Text _totemProb; // 0x58
	private Text _relicDevLevel; // 0x60
	private Image[] _buffIconImages; // 0x68
	private Sprite _lockedBuffSprite; // 0x70
	private Text _buffActiveTips; // 0x78
	private UIAnimationLocation _buffSwitchAnim; // 0x80
	private RoguelikeTopicModeViewProperty m_cachedProp; // 0x90
	private Int32 m_currSel; // 0x98
	private Single m_animPos; // 0x9c
	private Tween m_animTween; // 0xa0
	private Func`2 <buffIconLoader>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_buffIconLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_buffIconLoader; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__FindBuffDifficultyModel; // 0x18
	private static DelegateBridge __Hotfix0__FindDificultyModel; // 0x20
	private static DelegateBridge __Hotfix0_UpdateSelect; // 0x28
	private static DelegateBridge __Hotfix0__TweenBuffIconTo; // 0x30
	private static DelegateBridge __Hotfix0_EventShowAddDetail; // 0x38
	private static DelegateBridge __Hotfix0_EventShowRules; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Func`2 buffIconLoader { get; set; }

	// RVA: 0x26a22ac VA: 0x7594cba2ac
	public Func`2 get_buffIconLoader() { }
	// RVA: 0x26a2314 VA: 0x7594cba314
	public Void set_buffIconLoader(Func`2 value) { }
	// RVA: 0x26a2398 VA: 0x7594cba398
	public Void Render(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26a2608 VA: 0x7594cba608
	private RoguelikeTopicDifficultyViewModel _FindBuffDifficultyModel(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26a26b4 VA: 0x7594cba6b4
	private RoguelikeTopicDifficultyViewModel _FindDificultyModel(RoguelikeTopicModeViewModel model, RoguelikeTopicMode mode, Int32 grade) { }
	// RVA: 0x26a27f4 VA: 0x7594cba7f4
	public Void UpdateSelect(RL03DifficultyViewModel difficulty, Int32 selectIdx, Boolean fastMode) { }
	// RVA: 0x26a2c88 VA: 0x7594cbac88
	private Void _TweenBuffIconTo(Int32 buffCnt, Boolean fastMode) { }
	// RVA: 0x26a2ee8 VA: 0x7594cbaee8
	public Void EventShowAddDetail() { }
	// RVA: 0x26a2fc0 VA: 0x7594cbafc0
	public Void EventShowRules() { }
	// RVA: 0x26a3098 VA: 0x7594cbb098
	public Void .ctor() { }
	// RVA: 0x26a3108 VA: 0x7594cbb108
	private Single <_TweenBuffIconTo>b__26_0() { }
	// RVA: 0x26a3110 VA: 0x7594cbb110
	private Void <_TweenBuffIconTo>b__26_1(Single value) { }
}
```