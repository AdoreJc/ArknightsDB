# CharacterInfoRightProfView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Single _preferHeight`

- `CharacterInfoRightProfHideView _profHideView`

- `CharacterInfoRightProfSpreadView _spreadView`

- `AnimationWrapper _animWrapper`

- `Image _backImg`

- `UnityEvent _onResetEquipId`

- `Int32 equipScrollSequenceNum`

- `Tween m_cacheTween`


## Methods

- `Void _OnHide()`

- `Void _OnShow()`

- `Void _TweenBackColor(Single)`

- `Void OnClickHide()`

- `Void OnClickShow()`

- `Single <_TweenBackColor>b__14_0()`

- `Void <_TweenBackColor>b__14_1(Single)`

- `Void <>xLuaBaseProxy_AllHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfView : CharacterInfoCommonObj
{
	private Single _preferHeight; // 0x2c
	private CharacterInfoRightProfHideView _profHideView; // 0x30
	private CharacterInfoRightProfSpreadView _spreadView; // 0x38
	private AnimationWrapper _animWrapper; // 0x40
	private Image _backImg; // 0x48
	private UnityEvent _onResetEquipId; // 0x50
	public Int32 equipScrollSequenceNum; // 0x58
	private Tween m_cacheTween; // 0x60
	private const String ANIM_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_GetHeight; // 0x0
	private static DelegateBridge __Hotfix0_AllHide; // 0x8
	private static DelegateBridge __Hotfix0_ApplyViewModel; // 0x10
	private static DelegateBridge __Hotfix0__OnHide; // 0x18
	private static DelegateBridge __Hotfix0__OnShow; // 0x20
	private static DelegateBridge __Hotfix0__TweenBackColor; // 0x28
	private static DelegateBridge __Hotfix0_OnClickHide; // 0x30
	private static DelegateBridge __Hotfix0_OnClickShow; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2d83d64 VA: 0x759539bd64
	public override Single GetHeight() { }
	// RVA: 0x2d83dfc VA: 0x759539bdfc
	public override Void AllHide() { }
	// RVA: 0x2d83f4c VA: 0x759539bf4c
	public override Void ApplyViewModel(CharViewModel charViewModel) { }
	// RVA: 0x2d83e6c VA: 0x759539be6c
	private Void _OnHide() { }
	// RVA: 0x2d84170 VA: 0x759539c170
	private Void _OnShow() { }
	// RVA: 0x2d83ff4 VA: 0x759539bff4
	private Void _TweenBackColor(Single target) { }
	// RVA: 0x2d842a4 VA: 0x759539c2a4
	public Void OnClickHide() { }
	// RVA: 0x2d84324 VA: 0x759539c324
	public Void OnClickShow() { }
	// RVA: 0x2d843a4 VA: 0x759539c3a4
	public Void .ctor() { }
	// RVA: 0x2d84410 VA: 0x759539c410
	private Single <_TweenBackColor>b__14_0() { }
	// RVA: 0x2d8443c VA: 0x759539c43c
	private Void <_TweenBackColor>b__14_1(Single val) { }
	// RVA: 0x2d84448 VA: 0x759539c448
	private Void <>xLuaBaseProxy_AllHide() { }
}
```