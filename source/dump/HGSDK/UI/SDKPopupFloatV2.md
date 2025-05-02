# SDKPopupFloatV2

**Namespace:** `HGSDK.UI`


## Fields

- `CanvasGroup _alphaHandler`

- `SDKPopupTitleView _titleView`

- `FadeSwitchTween m_fadeTween`


## Properties

- `FadeSwitchTween fadeTween`


## Methods

- `FadeSwitchTween get_fadeTween()`

- `Void SetByHandler(FloatV2Handler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK.UI
public class SDKPopupFloatV2 : MonoBehaviour, IHotfixable
{
	private CanvasGroup _alphaHandler; // 0x18
	private SDKPopupTitleView _titleView; // 0x20
	private FadeSwitchTween m_fadeTween; // 0x28
	private static DelegateBridge __Hotfix0_get_fadeTween; // 0x0
	private static DelegateBridge __Hotfix0_SetByHandler; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	protected FadeSwitchTween fadeTween { get; }

	// RVA: 0x375225c VA: 0x7595d6a25c
	protected FadeSwitchTween get_fadeTween() { }
	// RVA: 0x3752350 VA: 0x7595d6a350
	public Void SetByHandler(FloatV2Handler handler) { }
	// RVA: 0x37524f0 VA: 0x7595d6a4f0
	public Void .ctor() { }
}
```