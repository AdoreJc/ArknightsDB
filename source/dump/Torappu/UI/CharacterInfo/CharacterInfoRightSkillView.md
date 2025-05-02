# CharacterInfoRightSkillView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _preferHeight`

- `CharacterInfoRightSkillHideView _hideView`

- `CharacterInfoRightSkillSpreadView _spreadView`

- `AnimationWrapper _animWrapper`

- `Image _backImg`

- `UnityEvent _onResetSkill`

- `Tween m_cacheTween`

- `CharViewModel m_cacheViewModel`


## Methods

- `Void _OnHide()`

- `Void _OnShow()`

- `Void _TweenBackColor(Single)`

- `Void OnClickHide()`

- `Void OnClickShow()`

- `Void <ApplyViewModel>b__10_0()`

- `Single <_TweenBackColor>b__14_0()`

- `Void <_TweenBackColor>b__14_1(Single)`

- `Void <>xLuaBaseProxy_AllHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightSkillView : CharacterInfoCommonObj, IHotfixable
{
	private Single _preferHeight; // 0x2c
	private CharacterInfoRightSkillHideView _hideView; // 0x30
	private CharacterInfoRightSkillSpreadView _spreadView; // 0x38
	private AnimationWrapper _animWrapper; // 0x40
	private Image _backImg; // 0x48
	private UnityEvent _onResetSkill; // 0x50
	private Tween m_cacheTween; // 0x58
	private CharViewModel m_cacheViewModel; // 0x60
	private const String ANIM_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_AllHide; // 0x0
	private static DelegateBridge __Hotfix0_ApplyViewModel; // 0x8
	private static DelegateBridge __Hotfix0_GetHeight; // 0x10
	private static DelegateBridge __Hotfix0__OnHide; // 0x18
	private static DelegateBridge __Hotfix0__OnShow; // 0x20
	private static DelegateBridge __Hotfix0__TweenBackColor; // 0x28
	private static DelegateBridge __Hotfix0_OnClickHide; // 0x30
	private static DelegateBridge __Hotfix0_OnClickShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d8444c VA: 0x759539c44c
	public override Void AllHide() { }
	// RVA: 0x2d8459c VA: 0x759539c59c
	public override Void ApplyViewModel(CharViewModel charViewModel) { }
	// RVA: 0x2d84a30 VA: 0x759539ca30
	public override Single GetHeight() { }
	// RVA: 0x2d844bc VA: 0x759539c4bc
	private Void _OnHide() { }
	// RVA: 0x2d84da0 VA: 0x759539cda0
	private Void _OnShow() { }
	// RVA: 0x2d84c24 VA: 0x759539cc24
	private Void _TweenBackColor(Single target) { }
	// RVA: 0x2d84f6c VA: 0x759539cf6c
	public Void OnClickHide() { }
	// RVA: 0x2d84fd4 VA: 0x759539cfd4
	public Void OnClickShow() { }
	// RVA: 0x2d8503c VA: 0x759539d03c
	public Void .ctor() { }
	// RVA: 0x2d850a8 VA: 0x759539d0a8
	private Void <ApplyViewModel>b__10_0() { }
	// RVA: 0x2d850b0 VA: 0x759539d0b0
	private Single <_TweenBackColor>b__14_0() { }
	// RVA: 0x2d850dc VA: 0x759539d0dc
	private Void <_TweenBackColor>b__14_1(Single val) { }
	// RVA: 0x2d850e8 VA: 0x759539d0e8
	private Void <>xLuaBaseProxy_AllHide() { }
}
```