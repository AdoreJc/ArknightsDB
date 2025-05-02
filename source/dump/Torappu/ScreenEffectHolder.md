# ScreenEffectHolder

**Namespace:** `Torappu`


## Fields

- `Boolean _enabled`

- `GameObject _effectToLoad`

- `GameObject m_effectInst`


## Properties

- `Boolean isEnabled`


## Methods

- `Boolean get_isEnabled()`

- `Void Awake()`

- `Void SetEffectEnable(Boolean)`

- `Void _EnableEffect()`

- `Void _DisableEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ScreenEffectHolder : MonoBehaviour, IHotfixable
{
	private Boolean _enabled; // 0x18
	private GameObject _effectToLoad; // 0x20
	private GameObject m_effectInst; // 0x28
	private static DelegateBridge __Hotfix0_get_isEnabled; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_SetEffectEnable; // 0x10
	private static DelegateBridge __Hotfix0__EnableEffect; // 0x18
	private static DelegateBridge __Hotfix0__DisableEffect; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isEnabled { get; }

	// RVA: 0x2d14b58 VA: 0x759532cb58
	public Boolean get_isEnabled() { }
	// RVA: 0x2d14bc0 VA: 0x759532cbc0
	private Void Awake() { }
	// RVA: 0x2d14c54 VA: 0x759532cc54
	public Void SetEffectEnable(Boolean enable) { }
	// RVA: 0x2d14d40 VA: 0x759532cd40
	private Void _EnableEffect() { }
	// RVA: 0x2d14e58 VA: 0x759532ce58
	private Void _DisableEffect() { }
	// RVA: 0x2d14f10 VA: 0x759532cf10
	public Void .ctor() { }
}
```