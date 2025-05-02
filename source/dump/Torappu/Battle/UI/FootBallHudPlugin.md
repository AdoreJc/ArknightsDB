# FootBallHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `AnimationWrapper _animWrapper`

- `Image _fillImage`

- `Image _shootImage`


## Methods

- `Void Reset()`

- `Void OnForceVectorChanged(FP, FP, FP)`

- `Void OnKnockBackByDamage()`

- `Void _OnShootEnd(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class FootBallHudPlugin : UnitTalentUIPlugin
{
	private RectTransform[] _performsRoots; // 0x30
	private AnimationWrapper _animWrapper; // 0x38
	private Image _fillImage; // 0x40
	private Image _shootImage; // 0x48
	private const String SHOOT_ANIM; // 0x0
	private const String HIT_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_OnForceVectorChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnKnockBackByDamage; // 0x10
	private static DelegateBridge __Hotfix0__OnShootEnd; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x201a170 VA: 0x7594632170
	public Void Reset() { }
	// RVA: 0x201a230 VA: 0x7594632230
	public Void OnForceVectorChanged(FP vectorX, FP vectorY, FP ratio) { }
	// RVA: 0x201a634 VA: 0x7594632634
	public Void OnKnockBackByDamage() { }
	// RVA: 0x201a7c4 VA: 0x75946327c4
	private Void _OnShootEnd(String args) { }
	// RVA: 0x201a850 VA: 0x7594632850
	public Void .ctor() { }
}
```