# EffectLightController

**Namespace:** `Torappu.Scripts.UI.Common`


## Fields

- `GameObject _anchorCenter`

- `GameObject _anchorBottom`


## Methods

- `Void SetCenterAnchorActive(Boolean)`

- `Void SetBottomAnchorActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.Common
public class EffectLightController : MonoBehaviour, IHotfixable
{
	private GameObject _anchorCenter; // 0x18
	private GameObject _anchorBottom; // 0x20
	private static DelegateBridge __Hotfix0_SetCenterAnchorActive; // 0x0
	private static DelegateBridge __Hotfix0_SetBottomAnchorActive; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x376e8fc VA: 0x7595d868fc
	public Void SetCenterAnchorActive(Boolean isActive) { }
	// RVA: 0x377645c VA: 0x7595d8e45c
	public Void SetBottomAnchorActive(Boolean isActive) { }
	// RVA: 0x37764e0 VA: 0x7595d8e4e0
	public Void .ctor() { }
}
```