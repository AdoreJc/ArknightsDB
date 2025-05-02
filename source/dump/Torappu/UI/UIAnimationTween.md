# UIAnimationTween

**Namespace:** `Torappu.UI`


## Fields

- `Tween m_handler`

- `Single m_tweenValue`

- `AnimationHandler m_animationHandler`

- `GameObject m_animTarget`


## Properties

- `Tween handler`


## Methods

- `Tween get_handler()`

- `Single GetValue()`

- `Void _ConstructorImpl(GameObject, AnimationHandler, Single, Options)`

- `Void _TryFireAnimationEvents(GameObject, Single, Single, Single)`

- `Void _FireAnimationEvent(GameObject, AnimationEvent)`

- `Void _SetValue(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAnimationTween : IHotfixable, ILuaCallCSharp
{
	public static readonly Options DEFAULT_OPTION; // 0x0
	private Tween m_handler; // 0x10
	private Single m_tweenValue; // 0x18
	private AnimationHandler m_animationHandler; // 0x20
	private GameObject m_animTarget; // 0x28
	private List`1 m_eventsToFire; // 0x30
	private static DelegateBridge __Hotfix0_get_handler; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18
	private static DelegateBridge _c__Hotfix1_ctor; // 0x20
	private static DelegateBridge _c__Hotfix2_ctor; // 0x28
	private static DelegateBridge _c__Hotfix3_ctor; // 0x30
	private static DelegateBridge __Hotfix0_GetValue; // 0x38
	private static DelegateBridge __Hotfix0__ConstructorImpl; // 0x40
	private static DelegateBridge __Hotfix0__CollectEventsToFire; // 0x48
	private static DelegateBridge __Hotfix0__TryFireAnimationEvents; // 0x50
	private static DelegateBridge __Hotfix0__FireAnimationEvent; // 0x58
	private static DelegateBridge __Hotfix0__SetValue; // 0x60

	public Tween handler { get; }

	// RVA: 0x2173938 VA: 0x759478b938
	public Tween get_handler() { }
	// RVA: 0x2178ad0 VA: 0x7594790ad0
	private Void .ctor(GameObject target, AnimationClip clip, Single duration, Options options) { }
	// RVA: 0x2178e30 VA: 0x7594790e30
	public Void .ctor(GameObject target, UIAnimationLocation anim) { }
	// RVA: 0x217674c VA: 0x759478e74c
	public Void .ctor(GameObject target, UIAnimationLocation anim, Single duration) { }
	// RVA: 0x2173830 VA: 0x759478b830
	public Void .ctor(GameObject target, UIAnimationLocation anim, Single duration, Options options) { }
	// RVA: 0x2178efc VA: 0x7594790efc
	public Single GetValue() { }
	// RVA: 0x2178bb8 VA: 0x7594790bb8
	private Void _ConstructorImpl(GameObject target, AnimationHandler handler, Single duration, Options options) { }
	// RVA: 0x2178f74 VA: 0x7594790f74
	private static List`1 _CollectEventsToFire(AnimationHandler handler) { }
	// RVA: 0x21791b4 VA: 0x75947911b4
	private Void _TryFireAnimationEvents(GameObject target, Single fromLerp, Single toLerp, Single clipLength) { }
	// RVA: 0x21793a0 VA: 0x75947913a0
	private Void _FireAnimationEvent(GameObject target, AnimationEvent evt) { }
	// RVA: 0x21795d4 VA: 0x75947915d4
	private Void _SetValue(Single value) { }
	// RVA: 0x21796e8 VA: 0x75947916e8
	private static Void .cctor() { }
}
```