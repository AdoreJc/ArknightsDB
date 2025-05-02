# CharacterInfoRightHolderView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoRightProfView _profView`

- `CharacterInfoRightLevelView _levelView`

- `CharacterInfoRightSkillView _skillView`

- `CharacterInfoRightEvolvePotentialView _evolvePotentialView`

- `HeightTweenLayoutElement _heightBar`

- `ScrollRect _scrollRect`

- `RectTransform _content`

- `Boolean m_isInited`

- `Boolean m_currentSpread`

- `Tween m_cacheTween`

- `Tween m_cacheEmptyTween`


## Methods

- `Void _InitIfNot()`

- `Void OnEvolveStateChange()`

- `IEnumerator _EvolveStateChange()`

- `Void OnSkillStateChange()`

- `Void OnProfStateChange()`

- `Void _OnFocusShow(Single)`

- `Void DealWithHeightInfo(Boolean)`

- `Void SetHide()`

- `Single <_OnFocusShow>b__18_0()`

- `Void <_OnFocusShow>b__18_1(Single)`

- `Void <_OnFocusShow>b__18_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightHolderView : DataBinder`1, IHotfixable
{
	private CharacterInfoRightProfView _profView; // 0x20
	private CharacterInfoRightLevelView _levelView; // 0x28
	private CharacterInfoRightSkillView _skillView; // 0x30
	private CharacterInfoRightEvolvePotentialView _evolvePotentialView; // 0x38
	private HeightTweenLayoutElement _heightBar; // 0x40
	private ScrollRect _scrollRect; // 0x48
	private RectTransform _content; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_currentSpread; // 0x59
	private const Single EMPTY_HEIGHT; // 0x0
	private const Single EVOLVE_ENLARGE_TIME; // 0x0
	private Tween m_cacheTween; // 0x60
	private Tween m_cacheEmptyTween; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEvolveStateChange; // 0x8
	private static DelegateBridge __Hotfix0__EvolveStateChange; // 0x10
	private static DelegateBridge __Hotfix0_OnSkillStateChange; // 0x18
	private static DelegateBridge __Hotfix0_OnProfStateChange; // 0x20
	private static DelegateBridge __Hotfix0__OnFocusShow; // 0x28
	private static DelegateBridge __Hotfix0_DealWithHeightInfo; // 0x30
	private static DelegateBridge __Hotfix0_SetHide; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d81860 VA: 0x7595399860
	private Void _InitIfNot() { }
	// RVA: 0x2d819e8 VA: 0x75953999e8
	public Void OnEvolveStateChange() { }
	// RVA: 0x2d81a88 VA: 0x7595399a88
	private IEnumerator _EvolveStateChange() { }
	// RVA: 0x2d81b5c VA: 0x7595399b5c
	public Void OnSkillStateChange() { }
	// RVA: 0x2d81f70 VA: 0x7595399f70
	public Void OnProfStateChange() { }
	// RVA: 0x2d81c68 VA: 0x7595399c68
	private Void _OnFocusShow(Single target) { }
	// RVA: 0x2d81e70 VA: 0x7595399e70
	public Void DealWithHeightInfo(Boolean isInit) { }
	// RVA: 0x2d82058 VA: 0x759539a058
	public Void SetHide() { }
	// RVA: 0x2d820f8 VA: 0x759539a0f8
	public override Void OnValueChanged(CharInfoGroupProperty property) { }
	// RVA: 0x2d82244 VA: 0x759539a244
	public Void .ctor() { }
	// RVA: 0x2d822dc VA: 0x759539a2dc
	private Single <_OnFocusShow>b__18_0() { }
	// RVA: 0x2d82300 VA: 0x759539a300
	private Void <_OnFocusShow>b__18_1(Single val) { }
	// RVA: 0x2d82340 VA: 0x759539a340
	private Void <_OnFocusShow>b__18_2() { }
}
```