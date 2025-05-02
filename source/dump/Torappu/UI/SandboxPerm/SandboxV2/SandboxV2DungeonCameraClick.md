# SandboxV2DungeonCameraClick

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `OnCameraClickedDelegate OnCameraClicked`


## Methods

- `Void add_OnCameraClicked(OnCameraClickedDelegate)`

- `Void remove_OnCameraClicked(OnCameraClickedDelegate)`

- `Void OnPointerClick(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerDown(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonCameraClick : MonoBehaviour, IPointerClickHandler, IEventSystemHandler, IPointerDownHandler, IPointerUpHandler, IHotfixable
{
	private OnCameraClickedDelegate OnCameraClicked; // 0x18
	private static DelegateBridge __Hotfix0_add_OnCameraClicked; // 0x0
	private static DelegateBridge __Hotfix0_remove_OnCameraClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnPointerClick; // 0x10
	private static DelegateBridge __Hotfix0_OnPointerUp; // 0x18
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2514b40 VA: 0x7594b2cb40
	public Void add_OnCameraClicked(OnCameraClickedDelegate value) { }
	// RVA: 0x2514c1c VA: 0x7594b2cc1c
	public Void remove_OnCameraClicked(OnCameraClickedDelegate value) { }
	// RVA: 0x2514cf8 VA: 0x7594b2ccf8
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x2514da8 VA: 0x7594b2cda8
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x2514e20 VA: 0x7594b2ce20
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x2514e98 VA: 0x7594b2ce98
	public Void .ctor() { }
}
```