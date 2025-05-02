# PostEffectLoader

**Namespace:** `Torappu.PostEffect`


## Fields

- `Boolean _bloomEnabled`

- `Settings _bloomSettings`

- `Boolean _useDepth`

- `Boolean _useStencil`

- `MobileBloom m_bloom`


## Properties

- `Boolean bloomEnabled`


## Methods

- `Boolean get_bloomEnabled()`

- `Void _OnSettingChanged(SettingType)`

- `Void _UpdateBloomStatus()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.PostEffect
public class PostEffectLoader : MonoBehaviour, IHotfixable
{
	private Boolean _bloomEnabled; // 0x18
	private Settings _bloomSettings; // 0x20
	private Boolean _useDepth; // 0x28
	private Boolean _useStencil; // 0x29
	private MobileBloom m_bloom; // 0x30
	private static DelegateBridge __Hotfix0_get_bloomEnabled; // 0x0
	private static DelegateBridge __Hotfix0__OnSettingChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateBloomStatus; // 0x10
	private static DelegateBridge __Hotfix0_Start; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean bloomEnabled { get; }

	// RVA: 0x3566898 VA: 0x7595b7e898
	public Boolean get_bloomEnabled() { }
	// RVA: 0x3566900 VA: 0x7595b7e900
	private Void _OnSettingChanged(SettingType settingType) { }
	// RVA: 0x3566994 VA: 0x7595b7e994
	private Void _UpdateBloomStatus() { }
	// RVA: 0x3566b3c VA: 0x7595b7eb3c
	private Void Start() { }
	// RVA: 0x3566c84 VA: 0x7595b7ec84
	private Void OnDestroy() { }
	// RVA: 0x3566dc4 VA: 0x7595b7edc4
	public Void .ctor() { }
}
```