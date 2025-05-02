# DecoInfo

**Namespace:** ` `


## Fields

- `Single _endDistDelta`

- `Single _fadeDur`

- `CanvasGroup _decCanvas`

- `Boolean m_hasDeco`

- `FadeSwitchTween m_tween`


## Methods

- `Void Init()`

- `Void UpdateTween(Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DecoInfo : IHotfixable
{
	private Single _endDistDelta; // 0x10
	private Single _fadeDur; // 0x14
	private CanvasGroup _decCanvas; // 0x18
	private Boolean m_hasDeco; // 0x20
	private FadeSwitchTween m_tween; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_UpdateTween; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x21c3bb8 VA: 0x75947dbbb8
	public Void Init() { }
	// RVA: 0x21c3e54 VA: 0x75947dbe54
	public Void UpdateTween(Boolean inDirection, Single pos) { }
	// RVA: 0x21c4108 VA: 0x75947dc108
	public Void .ctor() { }
}
```