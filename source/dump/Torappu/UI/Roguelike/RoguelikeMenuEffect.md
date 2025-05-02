# RoguelikeMenuEffect

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Boolean _GetShowStatus()`

- `Void SetShow(RoguelikeMenuEffectControlSource, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuEffect : MonoBehaviour, IHotfixable
{
	private Boolean[] m_showStatus; // 0x18
	private Boolean m_inited; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__GetShowStatus; // 0x8
	private static DelegateBridge __Hotfix0_SetShow; // 0x10
	private static DelegateBridge __Hotfix0_SetShowInner; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2a7b250 VA: 0x7595093250
	private Void _InitIfNot() { }
	// RVA: 0x2a7b328 VA: 0x7595093328
	private Boolean _GetShowStatus() { }
	// RVA: 0x2a7a0b8 VA: 0x75950920b8
	public Void SetShow(RoguelikeMenuEffectControlSource src, Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2a7b3d0 VA: 0x75950933d0
	protected virtual Void SetShowInner(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2a7b464 VA: 0x7595093464
	public Void .ctor() { }
}
```