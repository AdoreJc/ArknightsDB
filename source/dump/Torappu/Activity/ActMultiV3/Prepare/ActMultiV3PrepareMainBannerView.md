# ActMultiV3PrepareMainBannerView

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `UIAnimationLocation _animIn`

- `UIAnimationLocation _animOut`

- `UIAnimationLocation _animSwitch`

- `TwoStateToggle _blackToggle`

- `GameObject _firstNode`

- `GameObject _noCharPickNode`

- `GameObject _squadNode`

- `Tween m_animTween`


## Properties

- `Boolean playing`


## Methods

- `Boolean get_playing()`

- `Void Play(ActMultiV3PrepareMainBannerType)`

- `Void _OnAnimEnd()`

- `Void OnDestroy()`

- `Void _ClearAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainBannerView : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _animIn; // 0x18
	private UIAnimationLocation _animOut; // 0x28
	private UIAnimationLocation _animSwitch; // 0x38
	private TwoStateToggle _blackToggle; // 0x48
	private GameObject _firstNode; // 0x50
	private GameObject _noCharPickNode; // 0x58
	private GameObject _squadNode; // 0x60
	private Tween m_animTween; // 0x68
	private static DelegateBridge __Hotfix0_get_playing; // 0x0
	private static DelegateBridge __Hotfix0_Play; // 0x8
	private static DelegateBridge __Hotfix0__OnAnimEnd; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0__ClearAnim; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean playing { get; }

	// RVA: 0x3162db4 VA: 0x759577adb4
	public Boolean get_playing() { }
	// RVA: 0x3162e30 VA: 0x759577ae30
	public Void Play(ActMultiV3PrepareMainBannerType bannerType) { }
	// RVA: 0x3163218 VA: 0x759577b218
	private Void _OnAnimEnd() { }
	// RVA: 0x3163290 VA: 0x759577b290
	private Void OnDestroy() { }
	// RVA: 0x3163188 VA: 0x759577b188
	private Void _ClearAnim() { }
	// RVA: 0x31632f8 VA: 0x759577b2f8
	public Void .ctor() { }
}
```