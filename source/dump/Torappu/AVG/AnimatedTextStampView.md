# AnimatedTextStampView

**Namespace:** `Torappu.AVG`


## Fields

- `AnimationWrapper _animationWrapper`

- `String _animationName`

- `String m_stampId`


## Properties

- `String stampId`


## Methods

- `String get_stampId()`

- `Void InitView(CmdParam, Action)`

- `Void Dismiss()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AnimatedTextStampView : MonoBehaviour, IHotfixable
{
	private Text[] _textArray; // 0x18
	private AnimationWrapper _animationWrapper; // 0x20
	private String _animationName; // 0x28
	private String m_stampId; // 0x30
	private static DelegateBridge __Hotfix0_get_stampId; // 0x0
	private static DelegateBridge __Hotfix0_InitView; // 0x8
	private static DelegateBridge __Hotfix0_Dismiss; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String stampId { get; }

	// RVA: 0x3e5337c VA: 0x759646b37c
	public String get_stampId() { }
	// RVA: 0x3e533e4 VA: 0x759646b3e4
	public Void InitView(CmdParam param, Action cb) { }
	// RVA: 0x3e53758 VA: 0x759646b758
	public Void Dismiss() { }
	// RVA: 0x3e537c8 VA: 0x759646b7c8
	public Void .ctor() { }
}
```