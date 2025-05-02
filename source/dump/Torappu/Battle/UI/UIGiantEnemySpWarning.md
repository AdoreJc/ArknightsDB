# UIGiantEnemySpWarning

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GiantBossInfoType _giantBossInfoType`

- `Image _spWarningGlow`

- `Image _spWarningIconYellow`

- `Image _spWarningIconYellow2`

- `Image _spWarningIconRed`

- `Image _spWarningIconRed2`

- `Image _spWarningLine`

- `Image _spWarningLine2`

- `Image _spWarningClaw`

- `UITextSlider m_spSlider`

- `Tween m_spWarningLineTween`

- `Tween m_spWarningTween`

- `Int32 m_spWarningStage`

- `Color m_spWarningIconColor`

- `Tween m_spSliderColorTween`


## Properties

- `Boolean isDefault`

- `Boolean isVgctrl`


## Methods

- `Boolean get_isDefault()`

- `Boolean get_isVgctrl()`

- `Void SetSpSliderWarningTween(Int32, Boolean)`

- `Void SetSpSliderStageWarningTweenByProgress(Single)`

- `Void Awake()`

- `Void DoAttach(UITextSlider)`

- `Void OnDestroy()`

- `Void <SetSpSliderWarningTween>b__28_4()`

- `Void <SetSpSliderWarningTween>b__28_9(Single)`

- `Void <SetSpSliderWarningTween>b__28_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIGiantEnemySpWarning : MonoBehaviour, IHotfixable
{
	private GiantBossInfoType _giantBossInfoType; // 0x18
	private Image _spWarningGlow; // 0x20
	private Image _spWarningIconYellow; // 0x28
	private Image _spWarningIconYellow2; // 0x30
	private Image _spWarningIconRed; // 0x38
	private Image _spWarningIconRed2; // 0x40
	private Image _spWarningLine; // 0x48
	private Image _spWarningLine2; // 0x50
	private Image _spWarningClaw; // 0x58
	private UITextSlider m_spSlider; // 0x60
	private static readonly Single s_spWarningRatio; // 0x0
	private Tween m_spWarningLineTween; // 0x68
	private Tween m_spWarningTween; // 0x70
	private Int32 m_spWarningStage; // 0x78
	private Color m_spWarningIconColor; // 0x7c
	private static readonly Color s_spWarningStage1Color; // 0x4
	private static readonly Color s_spWarningStage2Color; // 0x14
	private static readonly Single s_spWarningLineTargetWidth; // 0x24
	private static readonly Single s_spWarningLineTweenDuration; // 0x28
	private static readonly Single s_spWarningLoopTweenDuration; // 0x2c
	private Tween m_spSliderColorTween; // 0x90
	private static readonly Color s_spSliderStage0Color; // 0x30
	private static readonly Color s_spSliderStage1Color; // 0x40
	private static readonly Color s_spSliderStage2Color; // 0x50
	private static DelegateBridge __Hotfix0_get_isDefault; // 0x60
	private static DelegateBridge __Hotfix0_get_isVgctrl; // 0x68
	private static DelegateBridge __Hotfix0_SetSpSliderWarningTween; // 0x70
	private static DelegateBridge __Hotfix0_SetSpSliderStageWarningTweenByProgress; // 0x78
	private static DelegateBridge __Hotfix0_Awake; // 0x80
	private static DelegateBridge __Hotfix0_DoAttach; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public Boolean isDefault { get; }
	public Boolean isVgctrl { get; }

	// RVA: 0x208c498 VA: 0x75946a4498
	public Boolean get_isDefault() { }
	// RVA: 0x208c518 VA: 0x75946a4518
	public Boolean get_isVgctrl() { }
	// RVA: 0x208c598 VA: 0x75946a4598
	public Void SetSpSliderWarningTween(Int32 stageIndex, Boolean force) { }
	// RVA: 0x208d4fc VA: 0x75946a54fc
	public Void SetSpSliderStageWarningTweenByProgress(Single spProgress) { }
	// RVA: 0x208d600 VA: 0x75946a5600
	private Void Awake() { }
	// RVA: 0x208d6ac VA: 0x75946a56ac
	public Void DoAttach(UITextSlider slider) { }
	// RVA: 0x208d7a4 VA: 0x75946a57a4
	public Void OnDestroy() { }
	// RVA: 0x208d834 VA: 0x75946a5834
	public Void .ctor() { }
	// RVA: 0x208d8b4 VA: 0x75946a58b4
	private static Void .cctor() { }
	// RVA: 0x208d970 VA: 0x75946a5970
	private Void <SetSpSliderWarningTween>b__28_4() { }
	// RVA: 0x208d9e4 VA: 0x75946a59e4
	private Void <SetSpSliderWarningTween>b__28_9(Single val) { }
	// RVA: 0x208dc9c VA: 0x75946a5c9c
	private Void <SetSpSliderWarningTween>b__28_1(Single val) { }
}
```