# SandboxV2RiftTeamBuffItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _buffText`

- `GameObject _activeIconGo`

- `CanvasGroup _canvasGroup`

- `Single _activeAlpha`

- `Single _unactiveAlpha`


## Methods

- `Void Render(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftTeamBuffItem : MonoBehaviour, IHotfixable
{
	private Text _buffText; // 0x18
	private GameObject _activeIconGo; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private Single _activeAlpha; // 0x30
	private Single _unactiveAlpha; // 0x34
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25ff68c VA: 0x7594c1768c
	public Void Render(String text, Boolean isActive) { }
	// RVA: 0x25ff75c VA: 0x7594c1775c
	public Void .ctor() { }
}
```