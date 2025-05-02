# TransitionModule

**Namespace:** ` `


## Fields

- `Animation _animation`

- `Tween m_cacheAnimTransTween`

- `Single m_cacheAnimPos`

- `UIButton m_host`


## Methods

- `Void Awake(UIButton)`

- `Void OnStateChange(UISelectionState)`

- `Void _PlayAnim(AnimationClip)`

- `Single _GetAnimPos()`

- `Void _StartColorTween(Color, Boolean)`

- `Void _SetAnimState(AnimationClip, Single)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
private class TransitionModule
{
	public const String DISABLE_ANIM; // 0x0
	public const String PRESSED_ANIM; // 0x0
	public const String LONGPRESSED_ANIM; // 0x0
	public const String DEFAULT_ANIM; // 0x0
	public const Single FADE_COLOR_DURATION; // 0x0
	public static readonly TransItem[] DEFAULT_TRANS_LIST; // 0x0
	private Animation _animation; // 0x10
	private TransItem[] _transList; // 0x18
	private Tween m_cacheAnimTransTween; // 0x20
	private Single m_cacheAnimPos; // 0x28
	private UIButton m_host; // 0x30


	// RVA: 0x677cf98 VA: 0x7598d94f98
	public Void Awake(UIButton host) { }
	// RVA: 0x677cfa0 VA: 0x7598d94fa0
	public Void OnStateChange(UISelectionState state) { }
	// RVA: 0x677d4c0 VA: 0x7598d954c0
	private Void _PlayAnim(AnimationClip clip) { }
	// RVA: 0x677d674 VA: 0x7598d95674
	private Single _GetAnimPos() { }
	// RVA: 0x677d300 VA: 0x7598d95300
	private Void _StartColorTween(Color targetColor, Boolean instant) { }
	// RVA: 0x677d67c VA: 0x7598d9567c
	private Void _SetAnimState(AnimationClip clip, Single pos) { }
	// RVA: 0x677d73c VA: 0x7598d9573c
	public Void .ctor() { }
	// RVA: 0x677d744 VA: 0x7598d95744
	private static Void .cctor() { }
}
```