# SandboxV2ExpeditionEnsureItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `CanvasGroup _selectedChar`

- `CanvasGroup _unselectedChar`

- `Boolean m_isInited`

- `FadeSwitchTween m_unselectedTween`

- `FadeSwitchTween m_selectedTween`


## Methods

- `Void Render(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ExpeditionEnsureItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _selectedChar; // 0x18
	private CanvasGroup _unselectedChar; // 0x20
	private Boolean m_isInited; // 0x28
	private FadeSwitchTween m_unselectedTween; // 0x30
	private FadeSwitchTween m_selectedTween; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24881a0 VA: 0x7594aa01a0
	public Void Render(Boolean isSelected) { }
	// RVA: 0x248824c VA: 0x7594aa024c
	private Void _InitIfNot() { }
	// RVA: 0x24883a4 VA: 0x7594aa03a4
	public Void .ctor() { }
}
```