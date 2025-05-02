# BossRushStageDetailInfoView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `AnimationWrapper _animationWrapper`

- `Text _textStageTitle`

- `Text _textStageCode`

- `Text _textStageDesc`

- `TweenWrapper m_tweenWrapper`

- `String m_cachedStageGroupId`

- `BossRushStageType m_cachedType`

- `BossRushStageModel m_cachedStageModel`

- `Action <onEnemyDetailClick>k__BackingField`


## Properties

- `Action onEnemyDetailClick`


## Methods

- `Action get_onEnemyDetailClick()`

- `Void set_onEnemyDetailClick(Action)`

- `Void OnEnemyDetailClick()`

- `Void _RefreshView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailInfoView : DataBinder`1, IHotfixable
{
	private const String ANIM_HIDE; // 0x0
	private const String ANIM_SHOW; // 0x0
	private AnimationWrapper _animationWrapper; // 0x20
	private Text _textStageTitle; // 0x28
	private Text _textStageCode; // 0x30
	private Text _textStageDesc; // 0x38
	private TweenWrapper m_tweenWrapper; // 0x40
	private String m_cachedStageGroupId; // 0x48
	private BossRushStageType m_cachedType; // 0x50
	private BossRushStageModel m_cachedStageModel; // 0x58
	private Action <onEnemyDetailClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onEnemyDetailClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onEnemyDetailClick; // 0x8
	private static DelegateBridge __Hotfix0_OnEnemyDetailClick; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__RefreshView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onEnemyDetailClick { get; set; }

	// RVA: 0x2e72800 VA: 0x759548a800
	private Action get_onEnemyDetailClick() { }
	// RVA: 0x2e72868 VA: 0x759548a868
	public Void set_onEnemyDetailClick(Action value) { }
	// RVA: 0x2e728ec VA: 0x759548a8ec
	public Void OnEnemyDetailClick() { }
	// RVA: 0x2e7299c VA: 0x759548a99c
	public override Void OnValueChanged(BossRushStageDetailProperty property) { }
	// RVA: 0x2e72c2c VA: 0x759548ac2c
	private Void _RefreshView() { }
	// RVA: 0x2e72d2c VA: 0x759548ad2c
	public Void .ctor() { }
}
```