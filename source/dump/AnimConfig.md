# AnimConfig

**Namespace:** ` `


## Fields

- `ActMultiV3MapDiffType _diffType`

- `UIAnimationLocation _diffAnim`


## Properties

- `ActMultiV3MapDiffType diffType`

- `UIAnimationLocation diffAnim`


## Methods

- `ActMultiV3MapDiffType get_diffType()`

- `UIAnimationLocation get_diffAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class AnimConfig : IHotfixable
{
	private ActMultiV3MapDiffType _diffType; // 0x10
	private UIAnimationLocation _diffAnim; // 0x18
	private static DelegateBridge __Hotfix0_get_diffType; // 0x0
	private static DelegateBridge __Hotfix0_get_diffAnim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public ActMultiV3MapDiffType diffType { get; }
	public UIAnimationLocation diffAnim { get; }

	// RVA: 0x314fe98 VA: 0x7595767e98
	public ActMultiV3MapDiffType get_diffType() { }
	// RVA: 0x314ff00 VA: 0x7595767f00
	public UIAnimationLocation get_diffAnim() { }
	// RVA: 0x3150844 VA: 0x7595768844
	public Void .ctor() { }
}
```