# RoguelikeMenuButtonPlugin

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject _pnlCancel`

- `GameObject _pnlConfirm`

- `Action onCancel`

- `Action onConfirm`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuButtonPlugin : MonoBehaviour, IHotfixable
{
	private GameObject _pnlCancel; // 0x18
	private GameObject _pnlConfirm; // 0x20
	public Action onCancel; // 0x28
	public Action onConfirm; // 0x30
	private static DelegateBridge __Hotfix0_OnClickCancel; // 0x0
	private static DelegateBridge __Hotfix0_OnClickConfirm; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a3def0 VA: 0x7595055ef0
	public virtual Void OnClickCancel() { }
	// RVA: 0x2a3df74 VA: 0x7595055f74
	public virtual Void OnClickConfirm() { }
	// RVA: 0x2a3dff8 VA: 0x7595055ff8
	public virtual Void Render(Input config) { }
	// RVA: 0x2a3e0c8 VA: 0x75950560c8
	public Void .ctor() { }
}
```