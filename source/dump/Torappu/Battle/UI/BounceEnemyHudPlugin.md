# BounceEnemyHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `AnimationWrapper _animWrapper`

- `Image _fillImage`

- `Image _shootImage`

- `String SHOOT_ANIM`

- `String HIT_ANIM`


## Methods

- `Void OnAppliedFinalForce()`

- `Void _OnShootEnd(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class BounceEnemyHudPlugin : UnitTalentUIPlugin
{
	protected RectTransform[] _performsRoots; // 0x30
	protected AnimationWrapper _animWrapper; // 0x38
	protected Image _fillImage; // 0x40
	protected Image _shootImage; // 0x48
	protected String SHOOT_ANIM; // 0x50
	protected String HIT_ANIM; // 0x58
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_OnForceVectorChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnAppliedFinalForce; // 0x10
	private static DelegateBridge __Hotfix0__OnShootEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20194cc VA: 0x75946314cc
	public virtual Void Reset() { }
	// RVA: 0x201958c VA: 0x759463158c
	public virtual Void OnForceVectorChanged(IUIForceInfo forceInfo) { }
	// RVA: 0x20199d4 VA: 0x75946319d4
	public Void OnAppliedFinalForce() { }
	// RVA: 0x2019b60 VA: 0x7594631b60
	private Void _OnShootEnd(String args) { }
	// RVA: 0x2019bf4 VA: 0x7594631bf4
	public Void .ctor() { }
}
```