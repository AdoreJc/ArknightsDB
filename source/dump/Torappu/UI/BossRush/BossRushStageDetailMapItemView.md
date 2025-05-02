# BossRushStageDetailMapItemView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `AnimationWrapper _animationWrapper`

- `Text _textWaveId`

- `Image _imgMapPreview`

- `GameObject _panelSecondBossInfo`

- `String m_cachedStageGroupId`

- `Int32 m_cachedWaveId`

- `String m_cachedActId`

- `Boolean m_hasLoadPreview`


## Methods

- `Void set_onClick(Action`1)`

- `Void set_onDetailClick(Action`1)`

- `Void Render(BossRushStageDetailMapCache, Single, Int32)`

- `Void OnClick()`

- `Void OnDetailClick()`

- `Void _RefreshView()`

- `Void _LoadImageIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailMapItemView : MonoBehaviour, IHotfixable
{
	private const String ANIM_KEY; // 0x0
	private AnimationWrapper _animationWrapper; // 0x18
	private Text _textWaveId; // 0x20
	private Image _imgMapPreview; // 0x28
	private Text[] _bossName; // 0x30
	private Image[] _bossIcon; // 0x38
	private GameObject _panelSecondBossInfo; // 0x40
	private String m_cachedStageGroupId; // 0x48
	private Int32 m_cachedWaveId; // 0x50
	private String m_cachedActId; // 0x58
	private Boolean m_hasLoadPreview; // 0x60
	private List`1 m_bossIdList; // 0x68
	private Action`1 <onClick>k__BackingField; // 0x70
	private Action`1 <onDetailClick>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onDetailClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onDetailClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x30
	private static DelegateBridge __Hotfix0__RefreshView; // 0x38
	private static DelegateBridge __Hotfix0__LoadImageIfNeed; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onClick { get; set; }
	private Action`1 onDetailClick { get; set; }

	// RVA: 0x2e73de8 VA: 0x759548bde8
	private Action`1 get_onClick() { }
	// RVA: 0x2e73e50 VA: 0x759548be50
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2e73ed4 VA: 0x759548bed4
	private Action`1 get_onDetailClick() { }
	// RVA: 0x2e73f3c VA: 0x759548bf3c
	public Void set_onDetailClick(Action`1 value) { }
	// RVA: 0x2e73fc0 VA: 0x759548bfc0
	public Void Render(BossRushStageDetailMapCache data, Single currPos, Int32 waveId) { }
	// RVA: 0x2e74658 VA: 0x759548c658
	public Void OnClick() { }
	// RVA: 0x2e746f8 VA: 0x759548c6f8
	public Void OnDetailClick() { }
	// RVA: 0x2e741b8 VA: 0x759548c1b8
	private Void _RefreshView() { }
	// RVA: 0x2e74558 VA: 0x759548c558
	private Void _LoadImageIfNeed() { }
	// RVA: 0x2e74798 VA: 0x759548c798
	public Void .ctor() { }
}
```