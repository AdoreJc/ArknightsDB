# AVGDisplayableHolder

**Namespace:** `Torappu.AVG`


## Fields

- `Object m_holderObj`


## Methods

- `Void Display(Command)`

- `Void Dispose()`

- `Void _ProcessCommand(Command)`

- `Void _DisplayWithParam(AVGDisplayParam)`

- `Void _DisplayEffect(AVGDisplayParam, AVGControllerSceneCanvas)`

- `Void _DisplayBg(AVGDisplayParam, AVGControllerSceneCanvas)`

- `AVGControllerSceneCanvas _GetCanvas(AVGDisplaySlot)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGDisplayableHolder : MonoBehaviour, IHotfixable, IDisposable
{
	private const Single DEFAULT_FADETIME; // 0x0
	private Object m_holderObj; // 0x18
	private static DelegateBridge __Hotfix0_Display; // 0x0
	private static DelegateBridge __Hotfix0_Dispose; // 0x8
	private static DelegateBridge __Hotfix0__ProcessCommand; // 0x10
	private static DelegateBridge __Hotfix0__DisplayWithParam; // 0x18
	private static DelegateBridge __Hotfix0__DisplayEffect; // 0x20
	private static DelegateBridge __Hotfix0__DisplayBg; // 0x28
	private static DelegateBridge __Hotfix0__GetCanvas; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3e553bc VA: 0x759646d3bc
	public Void Display(Command command) { }
	// RVA: 0x3e55a4c VA: 0x759646da4c
	public Void Dispose() { }
	// RVA: 0x3e5543c VA: 0x759646d43c
	private Void _ProcessCommand(Command command) { }
	// RVA: 0x3e55c1c VA: 0x759646dc1c
	private Void _DisplayWithParam(AVGDisplayParam param) { }
	// RVA: 0x3e55ec8 VA: 0x759646dec8
	private Void _DisplayEffect(AVGDisplayParam param, AVGControllerSceneCanvas canvas) { }
	// RVA: 0x3e56100 VA: 0x759646e100
	private Void _DisplayBg(AVGDisplayParam param, AVGControllerSceneCanvas canvasEnum) { }
	// RVA: 0x3e55e34 VA: 0x759646de34
	private AVGControllerSceneCanvas _GetCanvas(AVGDisplaySlot slot) { }
	// RVA: 0x3e56874 VA: 0x759646e874
	public Void .ctor() { }
}
```