# Act1VAutoChessSettleGameDailyRewardView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `GameObject _rootPanel`

- `Text _progressText`

- `Text _targetText`

- `GameObject _progressPanel`

- `Slider _progressSlider`

- `Text _rewardCountText`

- `Single _playBarDuration`

- `UIAnimationLocation _playAnimation`

- `Boolean m_hasInited`

- `AnimationWrapper m_playWrapper`

- `Boolean m_hasAnim`

- `Int32 m_figureMoveStart`

- `Int32 m_figureMoveEnd`

- `Int32 m_figureVolume`

- `Single m_figureMovePosition`

- `Boolean m_complete`

- `Sequence m_sequence`


## Methods

- `Void Render(DailyRewardViewModel)`

- `Tween PlayAnim()`

- `Void _InitIfNot()`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameDailyRewardView : MonoBehaviour, IHotfixable
{
	private GameObject _rootPanel; // 0x18
	private Text _progressText; // 0x20
	private Text _targetText; // 0x28
	private GameObject _progressPanel; // 0x30
	private Slider _progressSlider; // 0x38
	private Text _rewardCountText; // 0x40
	private Single _playBarDuration; // 0x48
	private UIAnimationLocation _playAnimation; // 0x50
	private Boolean m_hasInited; // 0x60
	private AnimationWrapper m_playWrapper; // 0x68
	private Boolean m_hasAnim; // 0x70
	private Int32 m_figureMoveStart; // 0x74
	private Int32 m_figureMoveEnd; // 0x78
	private Int32 m_figureVolume; // 0x7c
	private Single m_figureMovePosition; // 0x80
	private Boolean m_complete; // 0x84
	private Sequence m_sequence; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__GetPosition; // 0x18
	private static DelegateBridge __Hotfix0__SetPosition; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x33460dc VA: 0x759595e0dc
	public Void Render(DailyRewardViewModel model) { }
	// RVA: 0x33463c8 VA: 0x759595e3c8
	public Tween PlayAnim() { }
	// RVA: 0x3346328 VA: 0x759595e328
	private Void _InitIfNot() { }
	// RVA: 0x33465a4 VA: 0x759595e5a4
	private Single _GetPosition() { }
	// RVA: 0x334660c VA: 0x759595e60c
	private Void _SetPosition(Single position) { }
	// RVA: 0x334672c VA: 0x759595e72c
	public Void .ctor() { }
}
```