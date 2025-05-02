# RL04DifficultySelectLeftView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `GameObject _buffActiveBg`

- `GameObject _buffDisactiveBg`

- `Text _bpNum`

- `Text _bossNum`

- `GameObject _addRoot`

- `Text _relicDevLevel`

- `Text _disasterLevel`

- `Text _weightDevLevel`

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

- `RoguelikeTopicDifficultyViewModel _FindDifficultyModel(RoguelikeTopicModeViewModel, RoguelikeTopicMode, Int32)`

- `Void UpdateSelect(RL04DifficultyViewModel, Int32, Boolean)`

- `Void _TweenBuffIconTo(Int32, Boolean)`

- `Void EventShowAddDetail()`

- `Void EventShowRules()`

- `Single <_TweenBuffIconTo>b__24_0()`

- `Void <_TweenBuffIconTo>b__24_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04DifficultySelectLeftView : MonoBehaviour, IHotfixable
{
	private GameObject _buffActiveBg; // 0x18
	private GameObject _buffDisactiveBg; // 0x20
	private Text _bpNum; // 0x28
	private Text _bossNum; // 0x30
	private GameObject _addRoot; // 0x38
	private Text _relicDevLevel; // 0x40
	private Text _disasterLevel; // 0x48
	private Text _weightDevLevel; // 0x50
	private Image[] _buffIconImages; // 0x58
	private Sprite _lockedBuffSprite; // 0x60
	private Text _buffActiveTips; // 0x68
	private UIAnimationLocation _buffSwitchAnim; // 0x70
	private RoguelikeTopicModeViewProperty m_cachedProp; // 0x80
	private Int32 m_currSel; // 0x88
	private Single m_animPos; // 0x8c
	private Tween m_animTween; // 0x90
	private Func`2 <buffIconLoader>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_buffIconLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_buffIconLoader; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__FindBuffDifficultyModel; // 0x18
	private static DelegateBridge __Hotfix0__FindDifficultyModel; // 0x20
	private static DelegateBridge __Hotfix0_UpdateSelect; // 0x28
	private static DelegateBridge __Hotfix0__TweenBuffIconTo; // 0x30
	private static DelegateBridge __Hotfix0_EventShowAddDetail; // 0x38
	private static DelegateBridge __Hotfix0_EventShowRules; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Func`2 buffIconLoader { get; set; }

	// RVA: 0x26eb5fc VA: 0x7594d035fc
	public Func`2 get_buffIconLoader() { }
	// RVA: 0x26eb664 VA: 0x7594d03664
	public Void set_buffIconLoader(Func`2 value) { }
	// RVA: 0x26eb6e8 VA: 0x7594d036e8
	public Void Render(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26eb84c VA: 0x7594d0384c
	private RoguelikeTopicDifficultyViewModel _FindBuffDifficultyModel(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26eb8f8 VA: 0x7594d038f8
	private RoguelikeTopicDifficultyViewModel _FindDifficultyModel(RoguelikeTopicModeViewModel model, RoguelikeTopicMode mode, Int32 grade) { }
	// RVA: 0x26eba3c VA: 0x7594d03a3c
	public Void UpdateSelect(RL04DifficultyViewModel difficulty, Int32 selectIdx, Boolean fastMode) { }
	// RVA: 0x26ebec8 VA: 0x7594d03ec8
	private Void _TweenBuffIconTo(Int32 buffCnt, Boolean fastMode) { }
	// RVA: 0x26ec128 VA: 0x7594d04128
	public Void EventShowAddDetail() { }
	// RVA: 0x26ec200 VA: 0x7594d04200
	public Void EventShowRules() { }
	// RVA: 0x26ec2d8 VA: 0x7594d042d8
	public Void .ctor() { }
	// RVA: 0x26ec348 VA: 0x7594d04348
	private Single <_TweenBuffIconTo>b__24_0() { }
	// RVA: 0x26ec350 VA: 0x7594d04350
	private Void <_TweenBuffIconTo>b__24_1(Single value) { }
}
```