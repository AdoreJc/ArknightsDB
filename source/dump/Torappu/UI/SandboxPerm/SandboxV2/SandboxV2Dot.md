# SandboxV2Dot

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Graphic _normalGraphic`

- `Graphic _selectedGraphic`

- `Graphic _completedGraphic`

- `Single _fadeDur`


## Methods

- `Void Render(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2Dot : MonoBehaviour, IHotfixable
{
	private Graphic _normalGraphic; // 0x18
	private Graphic _selectedGraphic; // 0x20
	private Graphic _completedGraphic; // 0x28
	private Single _fadeDur; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x24fe2c4 VA: 0x7594b162c4
	public Void Render(Boolean selected, Boolean complete) { }
	// RVA: 0x24fe3f4 VA: 0x7594b163f4
	public Void .ctor() { }
}
```