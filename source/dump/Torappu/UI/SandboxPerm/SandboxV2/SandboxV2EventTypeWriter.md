# SandboxV2EventTypeWriter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single _typeInterval`

- `Boolean m_isInited`

- `String m_cachedText`

- `Text m_text`

- `Tween m_textTween`


## Properties

- `Boolean isTyping`


## Methods

- `Boolean get_isTyping()`

- `Void BeginText(String, Single)`

- `Void TryFinish()`

- `Void ResetText(String)`

- `Void SetColor(Color)`

- `Void _InitIfNot()`

- `Void _BeginTextImp(String, Single)`

- `Void _ResetTweenImp()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EventTypeWriter : MonoBehaviour, IHotfixable
{
	private Single _typeInterval; // 0x18
	private Boolean m_isInited; // 0x1c
	private String m_cachedText; // 0x20
	private Text m_text; // 0x28
	private Tween m_textTween; // 0x30
	private static DelegateBridge __Hotfix0_get_isTyping; // 0x0
	private static DelegateBridge __Hotfix0_BeginText; // 0x8
	private static DelegateBridge __Hotfix0_TryFinish; // 0x10
	private static DelegateBridge __Hotfix0_ResetText; // 0x18
	private static DelegateBridge __Hotfix0_SetColor; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__BeginTextImp; // 0x30
	private static DelegateBridge __Hotfix0__ResetTweenImp; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isTyping { get; }

	// RVA: 0x255e768 VA: 0x7594b76768
	public Boolean get_isTyping() { }
	// RVA: 0x255e7e4 VA: 0x7594b767e4
	public Void BeginText(String text, Single delay) { }
	// RVA: 0x255eb4c VA: 0x7594b76b4c
	public Void TryFinish() { }
	// RVA: 0x255ecc4 VA: 0x7594b76cc4
	public Void ResetText(String text) { }
	// RVA: 0x255edc4 VA: 0x7594b76dc4
	public Void SetColor(Color color) { }
	// RVA: 0x255e8e8 VA: 0x7594b768e8
	private Void _InitIfNot() { }
	// RVA: 0x255e9a4 VA: 0x7594b769a4
	private Void _BeginTextImp(String text, Single delay) { }
	// RVA: 0x255ec24 VA: 0x7594b76c24
	private Void _ResetTweenImp() { }
	// RVA: 0x255eed8 VA: 0x7594b76ed8
	public Void .ctor() { }
}
```