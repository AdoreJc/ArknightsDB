# UIBossHudRL3

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UITextSlider _spSlider`

- `UIAtlasImage _avater`

- `UIAtlasImage _deadAvater`

- `UIAtlasImage _deadSpImage`

- `EnemySkill m_enemySkill`

- `Boolean m_hasActived`

- `Boolean m_enemyValid`

- `FP m_skillRemainingTime`

- `Boolean m_onSpellOn`

- `Boolean m_skillReady`

- `UIRoguelikePluginRL3 m_plugin`


## Properties

- `Boolean actived`

- `Boolean enemyValid`

- `Boolean onSpellOn`

- `Boolean skillReady`

- `FP skillRemainingTime`


## Methods

- `Boolean get_actived()`

- `Boolean get_enemyValid()`

- `Boolean get_onSpellOn()`

- `Void set_onSpellOn(Boolean)`

- `Boolean get_skillReady()`

- `Void set_skillReady(Boolean)`

- `FP get_skillRemainingTime()`

- `Void set_skillRemainingTime(FP)`

- `Void OnInit(UIRoguelikePluginRL3)`

- `Void SetData(Enemy, EnemySkill)`

- `Void UpdateData()`

- `Void _StartDeadTweenAnim()`

- `Void <_StartDeadTweenAnim>b__29_0()`

- `Void <_StartDeadTweenAnim>b__29_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBossHudRL3 : MonoBehaviour, IHotfixable
{
	private const Single FADE_TIME; // 0x0
	private UITextSlider _spSlider; // 0x18
	private UIAtlasImage _avater; // 0x20
	private UIAtlasImage _deadAvater; // 0x28
	private UIAtlasImage _deadSpImage; // 0x30
	private ObjectPtr`1 m_owner; // 0x38
	private EnemySkill m_enemySkill; // 0x48
	private Boolean m_hasActived; // 0x50
	private Boolean m_enemyValid; // 0x51
	private FP m_skillRemainingTime; // 0x58
	private Boolean m_onSpellOn; // 0x60
	private Boolean m_skillReady; // 0x61
	private UIRoguelikePluginRL3 m_plugin; // 0x68
	private static DelegateBridge __Hotfix0_get_actived; // 0x0
	private static DelegateBridge __Hotfix0_get_enemyValid; // 0x8
	private static DelegateBridge __Hotfix0_get_onSpellOn; // 0x10
	private static DelegateBridge __Hotfix0_set_onSpellOn; // 0x18
	private static DelegateBridge __Hotfix0_get_skillReady; // 0x20
	private static DelegateBridge __Hotfix0_set_skillReady; // 0x28
	private static DelegateBridge __Hotfix0_get_skillRemainingTime; // 0x30
	private static DelegateBridge __Hotfix0_set_skillRemainingTime; // 0x38
	private static DelegateBridge __Hotfix0_OnInit; // 0x40
	private static DelegateBridge __Hotfix0_SetData; // 0x48
	private static DelegateBridge __Hotfix0_UpdateData; // 0x50
	private static DelegateBridge __Hotfix0__StartDeadTweenAnim; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean actived { get; }
	public Boolean enemyValid { get; }
	public Boolean onSpellOn { get; set; }
	public Boolean skillReady { get; set; }
	public FP skillRemainingTime { get; set; }

	// RVA: 0x206fdac VA: 0x7594687dac
	public Boolean get_actived() { }
	// RVA: 0x206fe14 VA: 0x7594687e14
	public Boolean get_enemyValid() { }
	// RVA: 0x206fe7c VA: 0x7594687e7c
	public Boolean get_onSpellOn() { }
	// RVA: 0x206fee4 VA: 0x7594687ee4
	public Void set_onSpellOn(Boolean value) { }
	// RVA: 0x206ff74 VA: 0x7594687f74
	public Boolean get_skillReady() { }
	// RVA: 0x206ffdc VA: 0x7594687fdc
	public Void set_skillReady(Boolean value) { }
	// RVA: 0x2070090 VA: 0x7594688090
	public FP get_skillRemainingTime() { }
	// RVA: 0x20700f8 VA: 0x75946880f8
	public Void set_skillRemainingTime(FP value) { }
	// RVA: 0x2070174 VA: 0x7594688174
	public Void OnInit(UIRoguelikePluginRL3 plugin) { }
	// RVA: 0x20702c4 VA: 0x75946882c4
	public Void SetData(Enemy enemy, EnemySkill enemySkill) { }
	// RVA: 0x20704dc VA: 0x75946884dc
	public Void UpdateData() { }
	// RVA: 0x2070894 VA: 0x7594688894
	private Void _StartDeadTweenAnim() { }
	// RVA: 0x2070d08 VA: 0x7594688d08
	public Void .ctor() { }
	// RVA: 0x2070d78 VA: 0x7594688d78
	private Void <_StartDeadTweenAnim>b__29_0() { }
	// RVA: 0x2070da0 VA: 0x7594688da0
	private Void <_StartDeadTweenAnim>b__29_1() { }
}
```