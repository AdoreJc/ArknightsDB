# ActivityEntryAnimManager

**Namespace:** `Torappu.Activity`


## Fields

- `UITwoStepAnimation m_player`


## Methods

- `Void _InitIfNot()`

- `Void PlayLoopAnim(IActAnimContext)`

- `Void PlayEnterAnim(IActAnimContext, Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityEntryAnimManager : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation[] _enterAnimList; // 0x18
	private UIAnimationLocation[] _loopAnimList; // 0x20
	private UITwoStepAnimation m_player; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_PlayLoopAnim; // 0x8
	private static DelegateBridge __Hotfix0_PlayEnterAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x30baa48 VA: 0x75956d2a48
	private Void _InitIfNot() { }
	// RVA: 0x30bab1c VA: 0x75956d2b1c
	public Void PlayLoopAnim(IActAnimContext context) { }
	// RVA: 0x30bacac VA: 0x75956d2cac
	public Void PlayEnterAnim(IActAnimContext context, Action completeCallback) { }
	// RVA: 0x30bae48 VA: 0x75956d2e48
	public Void .ctor() { }
}
```