# LuaLayout

**Namespace:** `Torappu.Lua`


## Fields

- `LuaUITransEffect _transEffect`

- `Button _sysCloseBtn`

- `ILuaLayoutEvent m_event`


## Properties

- `Button sysCloseButton`


## Methods

- `Button get_sysCloseButton()`

- `Void InjectDefines(IList`1, IList`1)`

- `Void BindLayoutEventListener(ILuaLayoutEvent)`

- `Void TraverseCtrlDefines(Action`2)`

- `Void TraverseValueDefines(Action`2)`

- `Void PlayTransInEffect()`

- `Void PlayTransOutEffect()`

- `Void ShowImmediatly()`

- `Void HideImmediatly()`

- `IEnumerator _TransIn()`

- `IEnumerator _TransOut()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void OnDestroy()`

- `Void OnResume()`

- `Void OnEnter()`

- `Void OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaLayout : MonoBehaviour
{
	private LuaUITransEffect _transEffect; // 0x18
	private Button _sysCloseBtn; // 0x20
	private ControllerDefine[] _ctrlDefines; // 0x28
	private ValueFieldDefine[] _valueDefines; // 0x30
	private ILuaLayoutEvent m_event; // 0x38
	private List`1 m_injectedCtrlDefines; // 0x40
	private List`1 m_injectedValueDefines; // 0x48

	public Button sysCloseButton { get; }

	// RVA: 0x35b54bc VA: 0x7595bcd4bc
	public Button get_sysCloseButton() { }
	// RVA: 0x35b54c4 VA: 0x7595bcd4c4
	public Void InjectDefines(IList`1 ctrlDefines, IList`1 valueDefines) { }
	// RVA: 0x VA: 0x0
	private static Void _SetInjectDefineList(IList`1 input, ref List`1 member) { }
	// RVA: 0x35b554c VA: 0x7595bcd54c
	public Void BindLayoutEventListener(ILuaLayoutEvent listener) { }
	// RVA: 0x35b5554 VA: 0x7595bcd554
	public Void TraverseCtrlDefines(Action`2 traverse) { }
	// RVA: 0x35b5674 VA: 0x7595bcd674
	public Void TraverseValueDefines(Action`2 traverse) { }
	// RVA: 0x35b5794 VA: 0x7595bcd794
	public Void PlayTransInEffect() { }
	// RVA: 0x35b5870 VA: 0x7595bcd870
	public Void PlayTransOutEffect() { }
	// RVA: 0x35b594c VA: 0x7595bcd94c
	public Void ShowImmediatly() { }
	// RVA: 0x35b59d0 VA: 0x7595bcd9d0
	public Void HideImmediatly() { }
	// RVA: 0x35b57fc VA: 0x7595bcd7fc
	private IEnumerator _TransIn() { }
	// RVA: 0x35b58d8 VA: 0x7595bcd8d8
	private IEnumerator _TransOut() { }
	// RVA: 0x35b5a54 VA: 0x7595bcda54
	private Void OnEnable() { }
	// RVA: 0x35b5afc VA: 0x7595bcdafc
	private Void OnDisable() { }
	// RVA: 0x35b5ba8 VA: 0x7595bcdba8
	private Void OnDestroy() { }
	// RVA: 0x35b37f8 VA: 0x7595bcb7f8
	public Void OnResume() { }
	// RVA: 0x35b5c58 VA: 0x7595bcdc58
	public Void OnEnter() { }
	// RVA: 0x35b5d04 VA: 0x7595bcdd04
	public Void OnExit() { }
	// RVA: 0x35b5db0 VA: 0x7595bcddb0
	public Void .ctor() { }
}
```