# Act1VAutoChessSettleGameLevelView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _levelText`

- `Text _expProgressText`

- `Text _expTargetText`

- `Slider _expProgressSlider`

- `GameObject _sliderPanel`

- `Single _playBarDuration`

- `UIAnimationLocation _levelUpAnimation`

- `UIAnimationLocation _levelMaxAnimation`

- `Boolean m_hasInited`

- `AnimationWrapper m_levelUpWrapper`

- `AnimationWrapper m_levelMaxWrapper`

- `Boolean m_hasAnim`

- `Single m_playPosition`

- `Int32 m_playLength`

- `Int32 m_playedLength`

- `Single m_playedVolume`

- `Int32 m_playItemCount`

- `Int32 m_playingItemIndex`

- `LevelPlayItem m_playingItem`

- `Int32 m_playingItemLength`

- `Single m_playingItemVolume`

- `Boolean m_levelUp`

- `Boolean m_levelMax`

- `Sequence m_sequence`

- `Tween m_levelUpTween`

- `Tween m_levelMaxTween`


## Methods

- `Void Render(LevelViewModel)`

- `Tween PlayAnim()`

- `Void _InitIfNot()`

- `Void _KillAllTweenIfNeed()`

- `Single _GetPosition()`

- `Void _SetPosition(Single)`

- `LevelPlayItem _RenderCurrentItem(Int32)`

- `Void _PlayLevelAnimationIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameLevelView : MonoBehaviour, IHotfixable
{
	private Text _levelText; // 0x18
	private Text _expProgressText; // 0x20
	private Text _expTargetText; // 0x28
	private Slider _expProgressSlider; // 0x30
	private GameObject _sliderPanel; // 0x38
	private Single _playBarDuration; // 0x40
	private UIAnimationLocation _levelUpAnimation; // 0x48
	private UIAnimationLocation _levelMaxAnimation; // 0x58
	private Boolean m_hasInited; // 0x68
	private AnimationWrapper m_levelUpWrapper; // 0x70
	private AnimationWrapper m_levelMaxWrapper; // 0x78
	private Boolean m_hasAnim; // 0x80
	private Single m_playPosition; // 0x84
	private Int32 m_playLength; // 0x88
	private Int32 m_playedLength; // 0x8c
	private Single m_playedVolume; // 0x90
	private List`1 m_playItems; // 0x98
	private Int32 m_playItemCount; // 0xa0
	private Int32 m_playingItemIndex; // 0xa4
	private LevelPlayItem m_playingItem; // 0xa8
	private Int32 m_playingItemLength; // 0xb8
	private Single m_playingItemVolume; // 0xbc
	private Boolean m_levelUp; // 0xc0
	private Boolean m_levelMax; // 0xc1
	private Sequence m_sequence; // 0xc8
	private Tween m_levelUpTween; // 0xd0
	private Tween m_levelMaxTween; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__KillAllTweenIfNeed; // 0x18
	private static DelegateBridge __Hotfix0__GetPosition; // 0x20
	private static DelegateBridge __Hotfix0__SetPosition; // 0x28
	private static DelegateBridge __Hotfix0__RenderCurrentItem; // 0x30
	private static DelegateBridge __Hotfix0__PlayLevelAnimationIfNeed; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3347e18 VA: 0x759595fe18
	public Void Render(LevelViewModel model) { }
	// RVA: 0x3348288 VA: 0x7595960288
	public Tween PlayAnim() { }
	// RVA: 0x33480e4 VA: 0x75959600e4
	private Void _InitIfNot() { }
	// RVA: 0x33481a0 VA: 0x75959601a0
	private Void _KillAllTweenIfNeed() { }
	// RVA: 0x3348468 VA: 0x7595960468
	private Single _GetPosition() { }
	// RVA: 0x33484d0 VA: 0x75959604d0
	private Void _SetPosition(Single position) { }
	// RVA: 0x33486f8 VA: 0x75959606f8
	private LevelPlayItem _RenderCurrentItem(Int32 positionOnLength) { }
	// RVA: 0x334887c VA: 0x759596087c
	private Void _PlayLevelAnimationIfNeed() { }
	// RVA: 0x3348980 VA: 0x7595960980
	public Void .ctor() { }
}
```