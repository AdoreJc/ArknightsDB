# MoveAnimGroup

**Namespace:** ` `


## Fields

- `UIAnimationLocation _enterAnim`

- `UIAnimationLocation _hideAnim`


## Methods

- `Void InitIfNot()`

- `Tween PlayWithTween(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MoveAnimGroup : IHotfixable
{
	private UIAnimationLocation _enterAnim; // 0x10
	private UIAnimationLocation _hideAnim; // 0x20
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_PlayWithTween; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x335b8bc VA: 0x75959738bc
	public Void InitIfNot() { }
	// RVA: 0x335b758 VA: 0x7595973758
	public Tween PlayWithTween(Action callBackOnHide) { }
	// RVA: 0x335c174 VA: 0x7595974174
	public Void .ctor() { }
}
```